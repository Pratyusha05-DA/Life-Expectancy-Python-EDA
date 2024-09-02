# Multiple Linear Regression on Life Expectancy
### Project Overview
This project aims to analyze the factors affecting life expectancy using Multiple Linear Regression. Life expectancy is a key indicator of the overall health and development of a country. By identifying and quantifying the impact of various predictors on life expectancy, the project provides insights that can help guide public health policies and resource allocation.

### Data Description
The dataset used in this project includes various predictors related to healthcare, lifestyle, and socio-economic factors. The key features of the dataset are:
* Healthcare Expenditures - Percentage of GDP spent on healthcare.
* Mortality Rates - Adult and infant mortality rates.
* Lifestyle Factors - Alcohol consumption, BMI (Body Mass Index).
* Educational Attainment - Average years of schooling.
* Immunization Coverage - Rates of vaccination for diseases like Hepatitis B, Polio, and Diphtheria.
* Economic Indicators - GDP, Income Composition of Resources.
* Demographic Information - Population density, total population.

### Domain Knowledge
* Life Expectancy: A critical measure of public health and development, reflecting the average number of years a person is expected to live based on current mortality rates.
* Predictors: Factors affecting life expectancy include healthcare-related variables, lifestyle choices, and educational attainment. Understanding these relationships helps in formulating policies to improve public health outcomes.
### Steps Followed
* **Data Collection -** Synthesized dataset covering key predictors and life expectancy.
* **Data Preprocessing -** 
    1. Cleaning: Handled missing values and outliers.
    2. Transformation: Adjusted data types and scaled numerical features.
* **Exploratory Data Analysis (EDA) -** 
    1. Conducted correlation analysis to identify key predictors.
    2. Visualized relationships between predictors and life expectancy using scatter plots and correlation matrices.
* **Model Building -**
    1. Built a Multiple Linear Regression model using the statsmodels library.
    2. Fit the model to the dataset to estimate the impact of each predictor on life expectancy.
* **Model Evaluation -**
    1. Assessed the model using R-squared, coefficients, and p-values to understand predictor significance and model fit.

### Key Insights
* R-squared Value - 0.527, indicating that 52.7% of the variance in life expectancy is explained by the model. This shows a moderate fit.
* Significant Predictors:
    * Adult Mortality - Strong negative impact, suggesting higher mortality rates decrease life expectancy.
    * Infant Deaths - Positive but unexpected; may require further investigation or data validation.
    * Alcohol Consumption - Shows a positive relationship with life expectancy, which could be influenced by socio-economic factors or data anomalies.
    * Schooling - Significant positive impact, emphasizing the importance of education on increasing life expectancy.
### Model Explanation
* **Model Type -** Multiple Linear Regression
* **Why Used -** This model is appropriate for predicting life expectancy based on multiple continuous predictors. It helps in understanding the strength and direction of relationships between life expectancy and various factors.
* **Benefits -** Provides clear insights into how each predictor affects life expectancy, allowing policymakers to target specific areas such as healthcare expenditure and education.
