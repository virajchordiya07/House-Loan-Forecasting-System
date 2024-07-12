# House-Loan-Forecasting-System
### Project Overview:
- The goal is to automate the loan eligibility process based on customer details provided during an online application.
- The details include Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, etc.
- The company aims to identify eligible customer segments to target specifically.

### Libraries and Data Import:
- Libraries imported: pandas, numpy, matplotlib, seaborn.
- Loan amounts are scaled by multiplying by 1000 for consistency.

### Initial Data Inspection:
- Summary statistics of the dataset are calculated.
- Checking for null values and counting them.
- Displaying dataset information and checking for duplicate entries.

### Exploratory Data Analysis (EDA):
- Distribution of loan status (approved or not) is visualized using a pie chart.
- A correlation heatmap is generated for selected numerical features to understand relationships between variables.

### Handling Missing Values:
- Missing values in various columns are identified and appropriate imputation techniques are applied.

### Feature Engineering:
- Creation of new features or transformation of existing ones to better represent the data for model training.

Data Preprocessing:
- Encoding categorical variables into numerical values using techniques such as one-hot encoding or label encoding.
- Scaling numerical features to standardize the data.

### Model Building:
- Various machine learning algorithms are applied to the processed data.
- Models considered include Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, etc.

### Model Evaluation:
- Evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are used to assess model performance.
- Cross-validation techniques are employed to ensure model robustness.

### Final Model Selection:
- Based on the evaluation, the best-performing model is selected.
- This model is then used for predicting loan eligibility on new data.
