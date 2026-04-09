# Credit-Card-Fraud-Detection

## About `app.py`
`app.py` is a Streamlit web application that detects whether a credit card transaction is legitimate or fraudulent. 

It performs the following key functions:
1. **Data Preprocessing**: Loads transaction data from `creditcard.csv` and balances the dataset by undersampling the majority class (legitimate transactions).
2. **Model Training**: Trains a Logistic Regression model on the balanced dataset.
3. **Web Interface**: Provides a Streamlit UI allowing users to input a comma-separated list of transaction features to receive a real-time prediction.

### How to run
You can start the web application by running:
```bash
streamlit run app.py
```