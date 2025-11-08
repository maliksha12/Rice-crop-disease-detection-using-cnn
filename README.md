# 🌾 Rice Crop Disease Detection using CNN

This project uses a Convolutional Neural Network (CNN) to detect and classify diseases in rice crop leaf images. The model learns visual features from healthy and diseased leaf samples to help identify crop issues early.

---

## 📘 Project Overview
- Data preprocessing and augmentation for robust training.
- Custom CNN model built using TensorFlow/Keras.
- Evaluation metrics: Accuracy, Precision, Recall, F1-score.
- Visualization of results including confusion matrix and accuracy/loss curves.

---

## 📊 Dataset
- Dataset contains rice leaf images categorized by disease types (e.g., Leaf Blast, Brown Spot, Bacterial Leaf Blight).
- File: `rice_crop_diseases_csv.zip`
- Dataset not uploaded to GitHub due to size limitations — upload or link to it externally (Kaggle, Drive, etc.).

---

## 📁 Repository Structure

```
rice-crop-disease-cnn/
│
├── notebooks/
│   └── Rice_Crop_Disease_Detection_using_CNN.ipynb
├── data/
│   └── rice_crop_diseases_csv.zip  # (or link to dataset)
├── src/
│   ├── model.py        # CNN model architecture
│   ├── train.py        # Training pipeline
│   └── evaluate.py     # Evaluation script
├── outputs/            # Plots, metrics, and figures
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

```bash
git clone https://github.com/maliksha12/rice-crop-disease-cnn.git
cd rice-crop-disease-cnn
pip install -r requirements.txt
```

---

## ▶️ Run the Project

1. Unzip dataset into `data/` folder.
2. Open the notebook:
   ```bash
   jupyter notebook notebooks/Rice_Crop_Disease_Detection_using_CNN.ipynb
   ```
3. Run all cells to preprocess data, train CNN, and evaluate results.

---

## 📈 Results Summary
- Achieved high accuracy in classifying rice leaf diseases.
- CNN model successfully differentiates between multiple disease types.
- Key visualizations include training curves and confusion matrices.

---

## 💡 Future Work
- Apply transfer learning (ResNet, VGG16, or MobileNet).
- Deploy model using Streamlit or Flask for live predictions.
- Extend dataset with field images for real-world accuracy.

---

## 📬 Author
Malik Sha Hussain  
📧 malikshahussain123@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/malik-sha-hussain-969a07237)

---


