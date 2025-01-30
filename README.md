# Fraud Detection using Machine Learning

This project focuses on detecting fraudulent transactions using machine learning techniques. The dataset used contains information about various transactions, including the amount, origin, destination, and balance details.

## Steps Performed

### 1. Handling Categorical Features
- Encoded categorical features for the transaction type.

### 2. Outlier Identification and Handling
- Identified and handled outliers using Z-Score values, as outliers can negatively impact the performance of the ML model.

### 3. Multicollinearity Check
- Checked for multicollinearity using Variance Inflation Factor (VIF) to ensure that independent variables are not highly correlated.

### 4. Data Preparation
- **Feature Selection**: Selected relevant features for the model.
- **Encoding Categorical Features**: Encoded categorical features for compatibility with the ML algorithms.
- **Data Splitting**: Split the dataset into training (70%) and testing (30%) sets.
- **Hyperparameters Tuning**: Adjusted hyperparameters like `n_estimators` to improve model accuracy.

### 5. Model Training
- Used Random Forest classifier to train the model. The algorithm can be altered based on business requirements.

### 6. Dropping Non-Useful Features

