# Machine Learning Analysis: 
## AI Job Salary Prediction
In this analysis, a machine learning model was developed to predict annual salaries for AI-related jobs based on various job and market characteristics. After performing data cleaning and exploratory data analysis, a Gradient Boosting regression model from scikit-learn was trained on the dataset.
The dataset included features such as years of experience, job category, demand score, benefits score, remote work availability, and other job attributes. These features were used as input variables to predict the target variable annual_salary_usd.
The dataset was first split into training and testing sets to evaluate model performance on unseen data. The Gradient Boosting model was then trained on the training set and used to generate salary predictions for the test set.
To evaluate the model’s performance, several metrics were used:
Mean Absolute Error (MAE): Measures the average difference between predicted and actual salaries.
Mean Squared Error (MSE): Penalizes larger prediction errors more strongly.
R² Score: Indicates how well the model explains the variance in salary values.
Additionally, feature importance analysis was performed to determine which variables most strongly influence salary predictions. The results indicated that factors such as years of experience, job demand score, and job category have a significant impact on salary levels.
The analysis demonstrates that machine learning techniques can effectively model salary trends in the AI job market and help identify the key factors that influence compensation.
