# Housing Price Prediction Project

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
- **Linear Regression (from scratch):** Manual implementation of linear regression.  
- **Ridge Regression (scikit-learn):** Regularized linear model to reduce overfitting.  
- **Ridge Regression (from scratch):** Manual implementation of Ridge regression.  
- **Online Machine Learning (SGDRegressor):** Model training on sequentially arriving data for real-time updates.

---

## Project Structure

The notebook is organized into sections for each dataset, including:

- Data loading and initial exploration  
- Exploratory Data Analysis (EDA) with visualizations (correlation heatmaps, scatter plots)  
- Model implementation and evaluation:
  - Linear Regression (scikit-learn and from scratch)  
  - Ridge Regression (scikit-learn and from scratch)  
  - Online ML (SGDRegressor)  
- Hyperparameter tuning with **GridSearchCV**  
- Model performance comparison using **Mean Squared Error (MSE)** and **R² scores**

---

## Key Findings

- Model performance varies across datasets.  
- Ridge regression with hyperparameter tuning generally performs best.  
- Manual implementations provide deeper algorithmic understanding.  
- Online ML enables incremental learning and real-time prediction updates.  

Refer to the notebook for detailed results, visualizations, and comparisons.

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

### Install them using:
```bash
pip install -r requirements.txt
```

---

## How to Run the Notebook

### 1. Clone this repository
```bash
git clone https://github.com/your-username/Housing-Prices-Prediction.git
cd Housing-Prices-Prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the notebook
```bash
jupyter notebook Housing_Prices_Prediction.ipynb
```

---

## Pro Tip for Recruiters / Collaborators

This project demonstrates **end-to-end workflow design**, **feature engineering**, **model implementation**, and **comparative analysis**, making it a **strong portfolio piece** for roles in **machine learning and applied data science**.

---

## Author

**Sumayya** — *M.Sc. in Artificial Intelligence*  
Passionate about applied AI, model interpretability, and real-world ML deployments.
