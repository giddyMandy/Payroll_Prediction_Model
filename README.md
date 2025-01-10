## Table of contents
-[Project Description](#project-description)
- [Dataset](#dataset)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature](#feature)
- [Model Building](#modelbuilding)
- [Model Performance](#modelperformance)
### Project description
This project involves building a payroll prediction model using linear regression. The objective is to estimate salaries based on historical data and key variables, leveraging statistical techniques to generate accurate forecasts and provide actionable insights.

### Dataset
This dataset contains information about a sample of individuals and their music preferences, including age, gender and genre.
data source: kaggle

### Tools
The following tools and libraries were utilized in this project: Python, NumPy, Pandas, Matplotlib, Seaborn and Scikit-learn

### Exploratory Data Analysis
- Getting a sence of the data types(numerical, categorical).
- Understanding the meaning and relevance of each feature (column).
- Identifying missing values.

### Feature
The key feature used for model building is years of experience.

### Model Building
1. Data Splitting: The dataset was split into 80% training and 20% testing using train_test_split.

2. Model Training: A model was selected and trained using the training data (feature_train, target_train).

3. Prediction: Predictions were made on the test set (feature_test).

   
### Model Performance
1. Evaluation Metric: The model's performance was evaluated using accuracy.

2. Results:

a. Coefficients: [9345.94244312]

The coefficient indicates the change in the dependent variable (salary) for a one-unit increase in the independent variable (e.g., years of experience)
In this case, for every one-unit increase in the feature, the predicted salary increases by approximately 9,345.94 units.

b. Intercept: 26816.192244031183

The intercept is the value of the dependent variable (salary) when the independent variable is/are zero.
Here, the base salary is approximately 26,816.19 units.

c. Mean Squared Error (MSE): 21026037.33

The MSE measures the average squared difference between the predicted and actual values.
A lower MSE indicates a better fit of the model to the data.
In this case, the MSE of 21,026,037.33 reflects the average squared error in your salary predictions.

d. Coefficient of Determination (R²): 0.97

R², or the Coefficient of Determination, indicates the proportion of the variance in the dependent variable (salary) explained by the independent variable(s).
An R² of 0.97 means that 97% of the variation in salary is explained by your model, which suggests an excellent fit.

Summary
The  model shows strong predictive performance with a high R² value, meaning it explains most of the variation in salary. However, the relatively high MSE suggests there may still be some room for improvement in prediction accuracy.
