# Bank Churn Customer Prediction

This project aims to predict **customer churn** in a banking system using machine learning classification models built in **Python**. By analyzing customer data, the goal is to predict whether a customer is likely to leave (churn) or stay with the bank, which can help the bank take proactive measures to retain valuable customers.

## Project Overview

The model is trained using a dataset of bank customers and various features such as customer demographic information, account details, and historical interactions with the bank. The project builds a classification model that predicts if a customer will churn or not.

### Key Steps:
1. **Data Preprocessing**:
   - Loading and inspecting the dataset.
   - Handling missing values and outliers.
   - Encoding categorical variables.
   - Splitting data into training and test sets.

2. **Model Building**:
   - Using machine learning algorithms (e.g., Random Forest, Logistic Regression) to predict churn.
   - Hyperparameter tuning to optimize model performance.
   - Evaluating model accuracy and effectiveness using various metrics.

3. **Evaluation**:
   - Performance evaluation using **Accuracy**, **Precision**, **Recall**, and **F1-score**.
   - Visualizing feature importance and churn patterns.

4. **Prediction**:
   - Making predictions on new/unseen customer data.

## Dataset

The dataset used in this project includes customer-related data such as:
- **Customer ID**
- **Account Type**
- **Credit Score**
- **Age**
- **Tenure** (Years with the bank)
- **Balance**
- **Number of Products**
- **Has Credit Card** (Yes/No)
- **Estimated Salary**
- **Exited** (Whether the customer churned or not)

> **Note**: The dataset used is synthetic and publicly available for educational purposes. The data can be found in the repository files.

## Libraries and Tools

This project uses the following libraries:
- **Pandas**: Data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Scikit-learn**: For building and evaluating classification models.
- **Google Colab** : For interactive development and testing.

Results

After training and evaluating the model, the results include:

Accuracy, Precision, Recall, and F1-Score for both training and test sets.

Insights on important features affecting customer churn.

Conclusion

This project demonstrates how machine learning can be applied to customer data for predicting churn in a banking environment. By leveraging classification models, the bank can make informed decisions about customer retention strategies.
