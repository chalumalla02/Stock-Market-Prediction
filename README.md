
# Stock Market Prediction Using Data Analytics & Machine Learning

## Overview
This project focuses on analyzing historical stock market data and applying data analytics and machine learning techniques to understand price trends and predict future stock prices. It demonstrates an end-to-end analytical workflow, from raw data preprocessing to model evaluation, using Python-based tools.

The project was developed as part of an academic IT project and refined to align with real-world data analyst and machine learning use cases.

---

## Objectives
- Analyze historical stock price trends and market behavior  
- Perform data cleaning and preprocessing on time-series data  
- Engineer features to enhance predictive performance  
- Build and compare multiple regression-based machine learning models  
- Visualize insights to support data-driven financial analysis  

---

## Tools & Technologies
- **Python**
- **Pandas, NumPy** – Data preprocessing and manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Model building and evaluation  
- **Jupyter Notebook** – Analysis and implementation  

---

## Dataset
- Historical stock market data containing:
  - Open, High, Low, Close prices  
  - Trading volume  
- Time-series structured data sourced from publicly available financial datasets  

---

## Methodology
1. **Data Preprocessing**  
   Cleaned raw data, handled missing values, formatted date columns, and normalized numerical features.

2. **Exploratory Data Analysis (EDA)**  
   Analyzed trends, volatility, and price movements using visualizations to understand market patterns.

3. **Feature Engineering**  
   Created derived features such as moving averages, lag values, and price differences to improve model accuracy.

4. **Model Development**  
   Implemented and compared regression models including:
   - Linear Regression  
   - Decision Tree Regression  
   - Random Forest Regression  
   - Gradient Boosting Regression  

5. **Model Evaluation**  
   Evaluated model performance using MAE, MSE, and RMSE metrics.

---

## Results & Insights
- Ensemble models such as **Random Forest** and **Gradient Boosting** outperformed basic linear models  
- Feature engineering significantly improved prediction performance  
- Visual analysis highlighted key trends, volatility periods, and market fluctuations  

---

## Project Structure
Stock-Market-Prediction/
│── Stock_Predection_Model.ipynb
│── data/
│── README.md


---

## How to Run
```bash
git clone https://github.com/chalumalla02/Stock-Market-Prediction.git
cd Stock-Market-Prediction
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Stock_Predection_Model.ipynb

