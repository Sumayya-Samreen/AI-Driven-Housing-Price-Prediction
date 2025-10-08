
# AI-Driven Housing Price Prediction

This project explores **multiple regression techniques** to predict housing prices using three different datasets: **Boston Housing**, **Ames Housing**, and **California Housing**.
The goal is to compare model performance and identify the most effective approach for each dataset.

---

## Datasets

- **Boston Housing Dataset:** Classic dataset containing housing data for the Boston area.
- **Ames Housing Dataset:** Comprehensive dataset with numerous features describing residential homes in Ames, Iowa.
- **California Housing Dataset:** Dataset containing housing prices for California districts.

---

## Methods Explored

Implemented and evaluated the following regression techniques:

- **Linear Regression (scikit-learn):** Standard linear model for predicting continuous variables.
- **Linear Regression (from scratch):** Manual implementation of linear regression to deepen algorithmic understanding.
- **Ridge Regression (scikit-learn):** Regularized linear model to reduce overfitting and improve generalization.
- **Ridge Regression (from scratch):** Manual implementation of Ridge regression for educational purposes.
- **Online Machine Learning (SGDRegressor):** Incremental learning on sequential data for adaptive, real-time predictions.

---

## Project Structure

The Jupyter notebook is organized into sections for each dataset, including:

- Data loading and initial exploration
- Exploratory Data Analysis (EDA) with visualizations (correlation heatmaps, scatter plots)
- Model implementation and evaluation:
  - Linear Regression (scikit-learn and from scratch)
  - Ridge Regression (scikit-learn and from scratch)
  - Online Machine Learning (SGDRegressor)
- Hyperparameter tuning with **GridSearchCV**
- Model performance comparison using **Mean Squared Error (MSE)** and **R² scores**

---

## Key Findings

- Model performance varies across datasets.
- Ridge Regression with hyperparameter tuning generally delivers the most robust predictions.
- Manual model implementations reinforce understanding of regression algorithms.
- Online Machine Learning enables adaptive and incremental predictions in real-time scenarios.

---

## Project Features

- End-to-end ML pipeline development
- Comparative analysis of multiple regression techniques
- Custom model implementation for algorithmic insight
- Real-time learning capability with SGDRegressor
- Interactive data exploration and visualizations
- Hyperparameter tuning for model optimization

---

## Dependencies

This project requires the following Python libraries:

```
pandas==2.3.3
numpy==2.3.3
matplotlib==3.10.6
scikit-learn==1.7.2
seaborn==0.13.2
```

### Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## How to Run the Notebook

### 1. Clone this repository
```bash
git clone https://github.com/Sumayya-Samreen/AI-Driven-Housing-Price-Prediction.git
cd AI-Driven-Housing-Price-Prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the notebook
```bash
jupyter notebook AI_Driven_Housing_Price_Prediction.ipynb
```

---

## Pro Tip for Recruiters / Collaborators

This project exemplifies a **complete machine learning workflow**; from data preprocessing and feature engineering to model development, evaluation, and deployment readiness. 
It highlights expertise in **data analysis, regression modeling, hyperparameter tuning, online machine learning, and interactive visualization**, making it a strong portfolio piece for roles in **machine learning, data science, and AI engineering**.

---

## Author

**Sumayya Samreen — M.Sc. in Artificial Intelligence**
Passionate about applied AI, model interpretability, and real-world machine learning solutions.
