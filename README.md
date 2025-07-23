# 🫀 End-to-End Heart Disease Classification Project

This is my first Data Science & Machine Learning project, where I built a classification model to predict the presence of heart disease based on clinical data. The goal is to help in early diagnosis of heart disease using patient attributes.

---

## 🚀 Project Overview

- **Objective**: Predict whether a patient has heart disease based on medical attributes.
- **Type**: Supervised Learning - Binary Classification
- **Tech Stack**:
  - Python (NumPy, Pandas, Matplotlib, Seaborn)
  - Scikit-learn
  - Jupyter Notebook

---

## 📊 Dataset

- **Source**: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Attributes**: 14 features including age, cholesterol, chest pain type, etc.
- **Target**: `target` (1 = disease, 0 = no disease)

---

## 📌 Workflow

1. **Data Loading & Exploration**
   - Handled missing values
   - Visualized class distribution and feature correlations

2. **Data Preprocessing**
   - Label encoding for categorical variables
   - Feature scaling with `StandardScaler`

3. **Model Training**
   - Tried multiple models: Logistic Regression, KNN, Random Forest, SVC
   - Tuned hyperparameters for best performance

4. **Model Evaluation**
   - Evaluated using Accuracy, Precision, Recall, F1-Score
   - Visualized confusion matrix and classification report

5. **Final Model**
   - Achieved high accuracy using **Random Forest Classifier**

---

## 📈 Results

| Metric       | Score |
|--------------|-------|
| Accuracy     | ✅ ~85-90% |
| F1 Score     | ✅ Good balance between precision and recall |
| ROC-AUC      | ✅ Model generalizes well |

---

## 📁 Project Structure

```

end-to-end-heart-disease-classification/
│
├── end-to-end-heart-disease-classification.ipynb
├── README.md
└── heart-disease.csv

````

---

## 📌 How to Run

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/end-to-end-heart-disease-classification.git
cd end-to-end-heart-disease-classification
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:

```bash
jupyter notebook
```

---

## 🙌 Acknowledgements

* Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
* Inspired by various Kaggle notebooks and ML tutorials

---

## ✨ Future Improvements

* Implement deep learning models (ANN)
* Add deployment using Streamlit or Flask
* Perform feature selection using SHAP/Feature Importance

---

## 🧑‍💻 Author

**Chintu Rai**
2nd Year B.E. in Information Science
Cambridge Institute of Technology, Bengaluru
📧 [chintu.23ise@cambridge.edu.in](mailto:chintu.23ise@cambridge.edu.in)
🌐 GitHub: [chinturai23](https://github.com/chinturai23)

---

⭐ *If you found this project useful, feel free to star the repo!*

```

