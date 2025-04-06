# ❤️ Kernel SVM Prediction for Heart Disease Detection

This machine learning project utilizes a **Kernelized Support Vector Machine (SVM)** to classify whether a person is likely to have heart disease based on various medical indicators. The model is trained on the [Heart Prediction Dataset](https://www.kaggle.com/datasets/shantanugarg274/heart-prediction-dataset-quantum) from Kaggle.

---

## 📊 Dataset Overview

The dataset consists of 7 columns, including:

- `Age`, `Gender`
- `BloodPressure`, `Cholesterol`
- `HeartRate`, `QuantumPatternFeature`
- **`HeartDisease`** (1 = heart disease, 0 = no heart disease)

📎 [Link to Dataset](https://www.kaggle.com/datasets/shantanugarg274/heart-prediction-dataset-quantum)

---

## 🧪 Project Workflow

1. **Data Preprocessing**
   - Checked and handled missing values
   - Encoded categorical features
   - Scaled numerical features using StandardScaler

2. **Model Training**
   - Kernel SVM using `scikit-learn`
   - RBF kernel for non-linear classification

3. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix

---

## 📈 Performance Summary

The Kernel SVM model shows strong capability in separating the classes, making it a powerful tool for heart disease classification.

---

### 🚀 Getting Started

#### 📥 Clone the Repository  
```bash
git clone https://github.com/sudeepsrawat/Kernel-SVM-for-Heart-Disease-Detection.git
cd Kernel-SVM-for-Heart-Disease-Detection
```

#### 📦 Install Dependencies  
```bash
pip install pandas numpy matplotlib scikit-learn
```

#### 📓 Run the Notebook  
```bash
jupyter notebook Classification_Kernel_SVM.ipynb
```
