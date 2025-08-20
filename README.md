# 🥔 Potato Disease Detection using CNN

This project uses a **Convolutional Neural Network (CNN)** to classify potato plant leaves as **healthy** or **diseased**.  
Trained on the **Kaggle Potato Leaf Disease Dataset**, the model achieved **~95% accuracy**.  
Data augmentation techniques were applied to improve performance and reduce overfitting.

---

## 📂 Project Structure

```bash
potato-disease-detection/
└── Potato_Disease_Detection.ipynb # Jupyter Notebook with full pipeline
```


---

## 📊 Dataset
- **Source**: [Kaggle - Potato Leaf Disease Dataset](https://www.kaggle.com)  
- Classes:
  - Healthy
  - Early Blight
  - Late Blight
- Fetched directly via Kaggle API in the notebook.

---

## 🧠 Model Highlights
- Built using **TensorFlow / Keras**
- CNN architecture with:
  - Convolution + ReLU Layers
  - MaxPooling
  - Dropout
  - Fully Connected Dense Layers
- Optimizer: **Adam**
- Loss Function: **Categorical Crossentropy**
- Achieved:
  - **Training Accuracy**: ~96%
  - **Validation Accuracy**: ~95%

---

## 🔄 Data Augmentation
To improve model generalization:
- Rotation  
- Zoom  
- Width & Height Shifts  
- Horizontal Flip  

---

## ▶️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/potato-disease-detection.git
   ```

2. Open the notebook
   ```bash
   jupyter notebook Potato_Disease_Detection.ipynb
  ```
3. Execute the cells

## Future work
- Integrate Transfer Learning (e.g., ResNet, EfficientNet) for higher accuracy
- Export model as .h5 or .tflite for deployment
- Build an inference pipeline for real-time predictions
- Deploy using Flask or Streamlit for a simple web interface
- Expand dataset with field images for better generalization
