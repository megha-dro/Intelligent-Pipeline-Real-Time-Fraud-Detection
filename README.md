# Intelligent-Pipeline-Real-Time-Fraud-Detection
A machine learning pipeline for real-time credit card fraud detection using SMOTE, feature selection, and model evaluation
## 🧹 Cleaned Dataset

The cleaned dataset used for this project is **`creditcard_cleaned.csv`**, created after preprocessing the original credit card fraud dataset.

### 🔧 Steps Performed
- Removed duplicate and null records  
- Handled missing values  
- Scaled numerical features  
- Encoded categorical variables (if any)  
- Balanced the dataset using **SMOTE**  

### 📁 File Details
- **File name:** `creditcard_cleaned.csv`  
- **Rows:** 284,807  
- **Columns:** 31  
- **Target column:** `Class` (0 = Genuine, 1 = Fraud)

### 📘 How to Use
If you want to reproduce the cleaned data:
1. Run the notebook **`1_data_preparation.ipynb`**  
2. The notebook will automatically generate `creditcard_cleaned.csv` in the project folder.  
3. This file is then used in **`3_model_training.ipynb`** for model fitting and evaluation.

---

