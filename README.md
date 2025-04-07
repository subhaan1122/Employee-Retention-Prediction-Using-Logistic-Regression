👩‍💼 HR Employee Attrition Prediction using Logistic Regression:

This project predicts whether an employee will leave a company based on HR data. It uses Logistic Regression, a simple and effective machine learning algorithm for binary classification.

📌 Overview:

Dataset: HR_comma_sep.csv
Objective: Predict employee attrition (left column)
Model: Logistic Regression (from scikit-learn)
Visualizations: Bar plots of attrition rates by salary and department

🧾 Features Used:

Feature:	Description
satisfaction_level: 	Employee satisfaction score
average_montly_hours: 	Monthly average working hours
promotion_last_5years: 	Was promoted in the last 5 years (0/1)
salary: 	Categorical - 'low', 'medium', 'high'

salary is one-hot encoded into:
salary_low, salary_medium, salary_high
Target column: left (1 = left the company, 0 = retained)

📊 Exploratory Data Analysis:

Attrition rate by salary level:
      "pd.crosstab(df.salary, df.left).plot(kind='bar')"

Attrition rate by department:
      "pd.crosstab(df.Department, df.left).plot(kind='bar')"

⚙️ Model Pipeline:

- Load and explore the dataset
- Visualize attrition trends
- Select relevant features
- One-hot encode the salary feature
- Split the data (30% training, 70% testing)
- Train a Logistic Regression model
- Evaluate model performance

📈 Accuracy:

- Model: LogisticRegression()
- Accuracy on test data: ~76% (may vary slightly with each run)

💡 Learnings:

- Practical use of logistic regression
- Handling categorical variables with one-hot encoding
- Visualizing class imbalance with bar charts
- Splitting data and evaluating prediction accuracy

🌟 Star this project if you found it helpful!

