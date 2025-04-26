# chemmolregressionpredictor
https://colab.research.google.com/drive/1i75lfHGCfpgwI3VENRJf0B3Mi8Kz9kXR?usp=sharing


# ChemMolRegression 🧪📊  
**Predicting Molecular Solubility using Linear Regression**

This project applies a machine learning model to predict the aqueous solubility (logS) of chemical molecules based on their molecular descriptors. The dataset is sourced from Delaney's solubility dataset and processed using `pandas` and `scikit-learn`.

---

## 📂 Project Structure

- `chemmolregression.ipynb`: Main Jupyter Notebook that performs data loading, cleaning, training, and prediction using linear regression.
- `README.md`: Project documentation (you're reading it!).

---

## 📌 Objectives

- Load and explore the molecular dataset.
- Separate features (X) and target variable (logS).
- Split data into training and testing sets.
- Train a Linear Regression model.
- Predict and evaluate solubility on unseen data.

---

## 📈 Dataset

- Source: [Delaney solubility dataset](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv)
- Contains:
  - Molecular descriptors (e.g., molecular weight, logP, H-bond donors)
  - Target: `logS` (aqueous solubility)

---

## 🛠️ Technologies Used

- Python 🐍
- pandas 📊
- scikit-learn 🤖
- Jupyter Note
