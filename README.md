# DataDose-Medical-Cost-Modeling
DataDose: Medical Cost Modeling is a data analytics project aimed at predicting medical insurance charges. It involves data cleaning, exploratory data analysis, and the development of linear regression models, including ridge regression, to enhance prediction accuracy using a medical insurance dataset.
"DataDose: Medical Cost Modeling" Project
Objective: The "DataDose: Medical Cost Modeling" project aims to analyze and model medical insurance charges using various statistical and machine learning techniques. By leveraging demographic and health-related attributes such as age, gender, BMI, number of children, smoking status, and region, the goal is to identify key factors that influence medical insurance charges and develop predictive models to estimate medical expenses.

Dataset Overview: The dataset used in this project is a modified version of the Medical Insurance Price Prediction dataset from Kaggle. It contains the following columns:

Age: Age of the insured (integer).

Gender: Encoded as 1 for Female and 2 for Male.

BMI: Body Mass Index (float).

No_of_Children: Number of children (integer).

Smoker: Encoded as 1 for Smoker and 2 for Non-smoker.

Region: Encoded as 1 for Northwest, 2 for Northeast, 3 for Southwest, and 4 for Southeast.

Charges: Insurance charges in USD (float).

Methodology:

Data Loading and Cleaning: The dataset is imported and cleaned by handling missing or blank entries, ensuring data quality.

Exploratory Data Analysis (EDA): Visualization and correlation analysis are performed to uncover relationships between variables and the target variable (charges). The project focuses on variables like smoking status, age, and BMI.

Model Development:

Linear Regression: Both single-variable and multi-variable linear regression models are used to predict insurance charges.

Ridge Regression: Ridge regression is applied to refine model performance and handle potential multicollinearity.

Model Evaluation: The models are evaluated using metrics such as R² (R-squared) and Mean Squared Error (MSE) to assess their accuracy and generalization.

Tools & Technologies Used:

Python for coding.

Pandas and NumPy for data manipulation and cleaning.

Matplotlib and Seaborn for data visualization.

Scikit-learn for machine learning models and performance evaluation.

Statsmodels for detailed statistical summaries (optional).

Conclusion: This project offers valuable insights into the primary factors that drive medical insurance costs and demonstrates the use of regression models to predict insurance charges. The project emphasizes data preprocessing, exploratory data analysis, and the application of machine learning techniques to real-world financial data. Through this, it showcases how data-driven approaches can be used to model and forecast healthcare-related financial outcomes, potentially benefiting the insurance sector and healthcare decision-making.
