# 🧬 Genetic Disease Risk Classifier

A **Machine Learning project** that predicts the risk of genetic diseases using genomic dataset features.
The model is trained to classify **five genetic diseases** using machine learning algorithms.

This project demonstrates **data preprocessing, classification models, explainable AI, and an interactive interface** for disease prediction.

---

## 🚀 Project Overview

Early detection of genetic diseases can significantly improve healthcare outcomes.
This project uses **machine learning techniques** to analyze genetic data and classify the disease category.

The model is trained on a dataset containing **five genetic diseases**, and it predicts which disease a sample is associated with.

### Project Workflow

1. Data preprocessing and cleaning
2. Feature scaling and transformation
3. Training machine learning models
4. Model evaluation and visualization
5. Explainable AI using **SHAP**
6. Interactive prediction interface using **Gradio**

---

## 🧠 Diseases Predicted

The model predicts the following **five diseases**:

| Label | Disease            |
| ----- | ------------------ |
| 0     | Thalassemia        |
| 1     | Hemophilia         |
| 2     | Breast Cancer      |
| 3     | Sickle Cell Anemia |
| 4     | Cystic Fibrosis    |

---

## 🤖 Machine Learning Models Used

The following models were implemented and evaluated:

* Logistic Regression
* Random Forest Classifier

### Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* AUC Score

---

## 📊 Explainable AI

To interpret the model’s predictions, the project uses:

**SHAP (SHapley Additive Explanations)**

This helps identify:

* Important genetic features
* Feature contributions to predictions
* Model transparency and interpretability

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* SHAP
* Gradio
* Joblib

---

## 📂 Project Structure

```
Genetic-Disease-Risk-Classifier
│
├── genetic_disease_prediction.ipynb
├── README.md
├── requirements.txt
└── dataset.csv
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/Shaunsajie/Genetic-Disease-Risk-Classifier.git
cd Genetic-Disease-Risk-Classifier
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Open the notebook in **Google Colab or Jupyter Notebook** and run all cells:

```
genetic_disease_prediction.ipynb
```

This will:

* Train the machine learning models
* Evaluate model performance
* Generate visualizations
* Launch the **Gradio interface**

---

## 🌐 Interactive Prediction Interface

A **Gradio interface** is implemented to allow users to input genetic parameters and receive **real-time disease predictions**.

This demonstrates how machine learning models can be converted into **interactive healthcare tools**.

---

## 🎓 Academic Context

This project was developed as part of **B.Tech in Artificial Intelligence & Data Science** coursework focusing on **AI applications in healthcare and genetic disease prediction**.

---

## 🔮 Future Improvements

Possible enhancements include:

* Expanding the dataset to include more genetic diseases
* Using **deep learning models** for genomic analysis
* Deploying the application on **cloud platforms**
* Building a full **web-based healthcare AI system**

---

## 👨‍💻 Author

**Shaun Saji**
B.Tech – Artificial Intelligence & Data Science

GitHub:
https://github.com/Shaunsajie
