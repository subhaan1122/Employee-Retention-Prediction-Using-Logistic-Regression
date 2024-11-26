This project uses logistic regression to analyze and predict whether an employee is likely to leave the organization based on factors like satisfaction level, average monthly hours, promotion history, and salary. The goal is to help HR teams identify key drivers of attrition and improve employee retention strategies.

-> Features:

1. Data Exploration:
- Provides a breakdown of employee attrition and retention across departments.
- Analyzes relationships between satisfaction levels, working hours, salary, and attrition.
  
2. Data Preprocessing:
- Encodes categorical variables (salary) using one-hot encoding.
- Prepares the dataset for training and testing.
  
3. Logistic Regression Model:
- Trains a Logistic Regression model to predict whether an employee will leave.
  
4. Evaluation:
- Uses model accuracy to assess performance on test data.

-> Technologies Used:

- Python: Programming language.
- Pandas: Data manipulation.
- Matplotlib: Data visualization.
- Scikit-learn: Machine learning library.

-> How It Works:

1. Data Loading and Exploration:
- Loads the HR dataset and explores employee attrition by department and other features.
  
2. Data Preprocessing:
- Encodes categorical variables (e.g., salary) using one-hot encoding.
- Prepares independent variables (X) and the target variable (y).
  
3. Model Training and Testing:
- Splits the dataset into training and test sets.
- Trains a Logistic Regression model on the training data.
  
4. Prediction and Evaluation:
- Makes predictions on test data.
- Evaluates the model's accuracy score to assess performance.

