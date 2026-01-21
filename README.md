Category-wise Central Sector Schemes Analysis under Union Budget (2021?22 to 2023?24)
Project Overview
This project presents a comprehensive data science?based analysis of India?s Union Budget, focusing on category-wise and ministry-wise Central Sector Schemes across three fiscal years: 2021?22, 2022?23, and 2023?24. The study combines exploratory data analysis, statistical evaluation, and machine learning regression techniques to understand historical expenditure patterns and predict future budget allocations.
The project demonstrates how data-driven and machine learning approaches can improve fiscal forecasting, enhance transparency, and support informed decision-making in public finance.

Objectives
* Analyze expenditure trends across ministries and central sector schemes
* Compare Actuals, Budget Estimates, and Revised Estimates
* Study revenue and capital expenditure distribution
* Identify top ministries and schemes based on budget allocation
* Detect trends, anomalies, and outliers in fiscal data
* Build and evaluate machine learning models for budget prediction
* Demonstrate the application of AI and ML in public finance analysis

Dataset Description
* Dataset Name: MRF 4B ? Union Budget Dataset
* Source: Ministry of Finance, Government of India
* Format: CSV
* Fiscal Years Covered:
o Actuals: 2021?22
o Budget Estimates: 2022?23
o Revised Estimates: 2022?23
o Budget Estimates (Target Variable): 2023?24
The dataset contains ministry-wise and scheme-wise financial allocations, including revenue expenditure, capital expenditure, and total expenditure. All monetary values are expressed in crores of rupees.

Tools and Technologies
* Programming Language: Python
* Development Environment: Jupyter Notebook
* Libraries Used:
o Pandas
o NumPy
o Matplotlib
o Seaborn
o Scikit-learn

Methodology
Data Preprocessing
* Removal of duplicate records
* Handling of missing values (less than 1%)
* Conversion of currency and numerical fields
* Verification of consistency across fiscal years
Exploratory Data Analysis
* Distribution analysis of fiscal variables
* Ministry-wise and scheme-wise expenditure comparison
* Revenue versus capital expenditure analysis
* Growth rate analysis across years
* Correlation analysis using heatmaps
* Pareto (80?20) analysis
* Outlier detection and dimensionality reduction using PCA
Machine Learning Pipeline
* Features Used:
o Actuals (2021?22 Total)
o Budget Estimates (2022?23 Total)
* Target Variable:
o Budget Estimates (2023?24 Total)
* Models Implemented:
o Linear Regression
o Ridge Regression
o Lasso Regression
o ElasticNet
o Decision Tree Regressor
o Random Forest Regressor
o Extra Trees Regressor
o Gradient Boosting Regressor
o XGBoost Regressor
o Support Vector Regressor (SVR)
* Evaluation Metrics:
o Rý Score
o Mean Absolute Error (MAE)
o Root Mean Squared Error (RMSE)
o Accuracy (%)
Ensemble models such as Random Forest and Extra Trees achieved the highest predictive performance, with Rý values exceeding 0.95.

Key Insights
* Budget allocation is highly right-skewed, with a small number of ministries controlling the majority of funds
* Revenue expenditure dominates overall spending, accounting for approximately 85% of total allocation
* Defence, Finance, Railways, and Home Affairs consistently receive the highest budget allocations
* Around 20% of ministries account for nearly 80% of total expenditure, validating the Pareto principle
* Strong positive correlation exists between consecutive year budget estimates
* Ensemble machine learning models effectively capture non-linear fiscal patterns and improve forecast accuracy

Project Structure
Union_Budget_DS_Project/
³
ÃÄÄ DS_Mini_Project_CA3.ipynb
ÃÄÄ MRF_4B_Union_Budget.csv
ÃÄÄ Mini_Project_DS.pdf
ÀÄÄ README.md

How to Run the Project
1. Install required libraries:
2. pip install pandas numpy matplotlib seaborn scikit-learn
3. Open Jupyter Notebook:
4. jupyter notebook
5. Run the notebook DS_Mini_Project_CA3.ipynb sequentially

Academic Information
* Course: Data Science
* Assessment: Continuous Assessment (CA)
* Degree: B.Tech Computer Science and Engineering
* Semester: VII
* Institution: Symbiosis Institute of Technology, Nagpur

Author
Tashu Paliwal
B.Tech Computer Science and Engineering
Symbiosis Institute of Technology, Nagpur

Disclaimer
This project is developed strictly for academic and educational purposes. The dataset used is publicly available government data, and the analysis does not represent official government forecasts.
