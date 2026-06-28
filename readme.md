Multiple Linear Regression – Multi-Channel Marketing Analysis
Project Overview
This project demonstrates the application of Multiple Linear Regression (MLR) using Python and the statsmodels library to analyze the relationship between multiple marketing channels and product sales. The objective is to identify how different marketing investments influence sales performance while controlling for the effects of other variables.
The project follows a complete data analysis workflow, including data exploration, multicollinearity assessment, regression model development, diagnostic testing, and business interpretation. The final outcome is a statistically validated regression model that provides evidence-based recommendations for marketing budget allocation.
________________________________________
Dataset Description
The dataset contains marketing expenditure and campaign information alongside corresponding sales figures. It consists of both numerical and categorical variables.
Variables
Variable	Description	Data Type
TV	TV advertising budget category (Low, Medium, High)	Categorical
Radio	Radio advertising expenditure	Numerical
Social Media	Social media advertising expenditure	Numerical
Influencer	Influencer marketing category (Nano, Micro, Macro, Mega)	Categorical
Sales	Product sales (target variable)	Numerical
Categorical variables are converted into dummy variables before fitting the regression model.
________________________________________
Project Objectives
The objectives of this project are to:
•	Load and explore the marketing dataset.
•	Perform exploratory data analysis (EDA).
•	Examine relationships among predictor variables.
•	Detect multicollinearity using correlation matrices and Variance Inflation Factor (VIF).
•	Build a Multiple Linear Regression model using Ordinary Least Squares (OLS).
•	Evaluate model performance using R-squared, Adjusted R-squared, and statistical significance tests.
•	Validate regression assumptions using diagnostic plots and statistical tests.
•	Interpret regression coefficients in a business context.
•	Provide evidence-based recommendations for optimizing marketing budget allocation.
________________________________________
Analytical Workflow
The notebook performs the following steps:
1.	Import required Python libraries.
2.	Load and inspect the dataset.
3.	Check for missing values.
4.	Perform exploratory data analysis.
5.	Encode categorical variables using one-hot encoding.
6.	Examine multicollinearity using:
o	Correlation Matrix
o	Variance Inflation Factor (VIF)
7.	Fit a Multiple Linear Regression model using statsmodels.
8.	Evaluate model performance using:
o	R-squared
o	Adjusted R-squared
o	Regression coefficients
o	p-values
9.	Validate model assumptions through:
o	Residual vs Fitted Plot
o	Histogram of Residuals
o	Q-Q Plot
o	Scale-Location Plot
o	Shapiro-Wilk Normality Test
o	Breusch-Pagan Test for Homoscedasticity
10.	Interpret findings and provide marketing recommendations.
________________________________________
Technologies Used
•	Python 3.x
•	Jupyter Notebook
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Statsmodels
•	SciPy
________________________________________
Environment Setup
Clone the repository
git clone https://github.com/yourusername/multiple-linear-regression-marketing.git

cd multiple-linear-regression-marketing
Install required packages
Using pip:
pip install pandas numpy matplotlib seaborn statsmodels scipy
Alternatively, install all dependencies at once using a requirements file:
pip install -r requirements.txt
________________________________________
Repository Structure
multiple-linear-regression-marketing/
│
├── multiple_regression_analysis.ipynb
├── marketing_sales_data.csv
├── README.md
└── requirements.txt
________________________________________
Model Evaluation
The regression model is evaluated using several statistical measures, including:
•	R-squared
•	Adjusted R-squared
•	Coefficient estimates
•	p-values
•	Variance Inflation Factor (VIF)
•	Residual diagnostics
•	Normality assessment
•	Homoscedasticity tests
These metrics help assess model accuracy, statistical significance, and compliance with the assumptions of Multiple Linear Regression.
________________________________________
Business Insights
The analysis identifies which marketing channels contribute most significantly to sales performance while accounting for the influence of other predictors. The regression coefficients quantify the expected change in sales associated with each predictor, holding all other variables constant. These findings support data-driven marketing budget decisions by highlighting the channels that provide the greatest expected return on investment.
________________________________________
Future Improvements
Potential extensions of this project include:
•	Feature engineering
•	Interaction effects between marketing channels
•	Polynomial regression
•	Regularized regression techniques (Ridge and Lasso)
•	Cross-validation for improved model generalization
•	Machine learning model comparisons
________________________________________
License
This project is intended for educational purposes and demonstrates the implementation of Multiple Linear Regression using Python and the statsmodels library.

