#Project: Student Performance Prediction Using Linear and Logistic Regression

This project aims to predict student performance using Linear Regression and Logistic Regression, analyzing a dataset of 1,000 students with features such as gender, race/ethnicity, parental education level, and test scores in math, reading, and writing.

Key steps included data preprocessing, where new features for total and average scores were created. Students with perfect scores (100) were counted: 60 in math, 45 in reading, and 50 in writing. Data visualization highlighted the average score distribution, showing that students performed better in math compared to writing and reading.

Using ColumnTransformer, categorical variables were one-hot encoded, and numerical features were standardized. The Linear Regression model predicted math scores with a Mean Absolute Error (MAE) of 3.5 and an R-squared score of 0.85, indicating that 85% of the variance in math scores was explained by the model. The Logistic Regression model classified student performance, achieving an accuracy of 88% with a confusion matrix illustrating its effectiveness.

This project underscores the significance of data analysis in education, providing actionable insights for targeted student support and intervention.
