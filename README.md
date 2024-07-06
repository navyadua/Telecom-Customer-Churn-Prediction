# Telecom Customer Churn Prediction 📉📞

## Introduction 🚀

This project aims to develop a machine learning model to predict customer churn for a telecom company. Customer churn prediction is crucial for retaining valuable customers and improving business strategies. By leveraging a dataset containing various customer information and service details, we built a robust model to forecast which customers are likely to churn.

## Objectives 🎯

- **Primary Objective:** 
  - Develop a predictive model to identify customers who are likely to churn.
- **Secondary Objectives:**
  - Perform data preprocessing and exploratory data analysis.
  - Compare various machine learning models to select the best one.
  - Tune the selected model to improve its performance.
  - Evaluate the model and make predictions on the test dataset.

## Data Description 📄

The dataset comprises customer information and service details, including:
- **customerID:** Unique identifier for each customer.
- **gender:** Gender of the customer (Male, Female).
- **SeniorCitizen:** Binary indicator if the customer is a senior citizen (1 for yes, 0 for no).
- **Partner:** Binary indicator if the customer has a partner (Yes, No).
- **Dependents:** Binary indicator if the customer has dependents (Yes, No).
- **tenure:** Number of months the customer has been with the company.
- **PhoneService:** Binary indicator if the customer has phone service (Yes, No).
- **MultipleLines:** Indicator if the customer has multiple lines (Yes, No, No phone service).
- **InternetService:** Type of internet service (DSL, Fiber optic, No).
- **OnlineSecurity:** Binary indicator if the customer has online security (Yes, No, No internet service).
- **OnlineBackup:** Binary indicator if the customer has online backup (Yes, No, No internet service).
- **DeviceProtection:** Binary indicator if the customer has device protection (Yes, No, No internet service).
- **TechSupport:** Binary indicator if the customer has tech support (Yes, No, No internet service).
- **StreamingTV:** Binary indicator if the customer has streaming TV (Yes, No, No internet service).
- **StreamingMovies:** Binary indicator if the customer has streaming movies (Yes, No, No internet service).
- **Contract:** Type of contract (Month-to-month, One year, Two year).
- **PaperlessBilling:** Binary indicator if the customer has paperless billing (Yes, No).
- **PaymentMethod:** Payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
- **MonthlyCharges:** The amount charged to the customer monthly.
- **TotalCharges:** The total amount charged to the customer.
- **Churn:** Binary label indicating if the customer churned (Yes, No).

## Methodology 📈

### Data Exploration 🔍

Initial examination of the dataset to understand its structure, features, and statistical properties.

### Data Cleaning 🧼

- Handling missing values.
- Ensuring data quality.
- Converting categorical churn labels into binary format.

### Exploratory Data Analysis (EDA) 📊

- Visualizing the distribution of features.
- Understanding relationships between features and the target variable.

### Data Preprocessing 🔧

- Label encoding of categorical variables.
- Feature scaling and normalization.
- Splitting the data into training (80%) and test (20%) sets.

### Model Development 🤖

- **PyCaret Setup:** Initial setup with PCA for dimensionality reduction.
- **Model Comparison:** Comparing various models to select the best one.
- **Model Selection:** Chose Gradient Boosting Classifier (GBC) for its performance.
- **Model Tuning:** Hyperparameter tuning using GridSearchCV.
- **Model Evaluation:** Assessing the model using accuracy, precision, recall, F1 score, and confusion matrix.

### Predictions and Model Saving 🎯

- Making predictions on the test dataset.
- Saving the final model for future use.

## Results and Deliverables 📊

- **Model Performance Metrics:** Detailed evaluation of model performance.
- **Model Predictions:** Predictions on the test dataset.
- **Saved Model:** Gradient Boosting Classifier model saved as `gbc_model`.

## Conclusion 🌟

By developing a robust machine learning model, we successfully predicted customer churn for a telecom company. The project highlights the importance of data preprocessing, model comparison, and tuning in achieving high predictive accuracy. The final model provides valuable insights for the company to implement strategies to retain customers and reduce churn rates.

## Future Work 🔍

- **Feature Engineering:** Explore additional features that may improve model performance.
- **Advanced Models:** Experiment with more advanced models and deep learning techniques.
- **Real-time Predictions:** Implement the model for real-time churn prediction in a production environment.

---
Thank you for checking out our project!😉 We believe in creating a better world through technology⚙️, and we hope this project contributes to that goal.👍🏻
