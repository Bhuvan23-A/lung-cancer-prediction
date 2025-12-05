# **Lung Cancer Prediction**

This project builds an end-to-end machine learning pipeline to predict the likelihood of lung cancer based on clinical survey attributes. 
The workflow includes data preprocessing, feature scaling, model training, and performance evaluation using multiple supervised learning algorithms.

---

## 🚀 **Project Overview**

* Uses the **survey_lung_cancer.csv** dataset
* Performs data cleaning, handling missing values, and encoding categorical columns
* Applies **StandardScaler** to normalize feature distribution
* Trains and compares three ML models:

  * **Logistic Regression**
  * **Support Vector Machine (SVM)**
  * **K-Nearest Neighbors (KNN)**
* Computes accuracy metrics and identifies the best-performing model

---

## 📊 **Dataset**

The dataset contains patient symptoms and personal health indicators.
Target variable: **LUNG_CANCER** (Yes/No)

Key preprocessing steps:

* Dropped missing values
* Encoded the **GENDER** column using LabelEncoder
* Split data into **80% training** and **20% testing**
* Applied **StandardScaler** on numerical features

---

## 🧠 **Models Used**

### ✔️ Logistic Regression

* Iterations: `max_iter = 200`
* Good for interpretability

### ✔️ Support Vector Machine (Linear Kernel)

* Kernel: `linear`
* Provides strong margin-based classification

### ✔️ K-Nearest Neighbors

* Neighbors: `k = 5`

---

## 📈 **Results**

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~89%     |
| SVM (Linear)        | ~90%     |
| KNN (k=5)           | ~87%     |

**Best Model:** Support Vector Machine (highest overall test accuracy)

---

## 🛠️ **Technologies & Libraries**

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## 📂 **Project Structure**

```
├── Lung_Cancer_Prediction.ipynb
├── survey_lung_cancer.csv
└── README.md
```

---

## ▶️ **How to Run the Project**

1. Install required libraries:

   ```bash
   pip install numpy pandas scikit-learn
   ```
2. Open the notebook in Jupyter or Google Colab
3. Upload the dataset
4. Run all cells to train and evaluate the models

---

## 📬 **Contributions**

Contributions, issues, and suggestions are welcome!

