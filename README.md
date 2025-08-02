# churn-prediction
Machine Learning model to predict telecom customer churn using call duration, data usage, contract length and other data.

ConnectSphere Telecom - Customer Churn Prediction

This project predicts potential customer churn for **ConnectSphere Telecom** using machine learning techniques. The goal is to identify at-risk customers based on usage patterns and contract history, enabling better customer retention strategies.


Problem Statement

Customer churn is a key concern for telecom providers. This project builds a **binary classification model** that predicts whether a customer is likely to leave based on:

- Call Duration (minutes per month)
- Data Usage (GB per month)
- Contract Length (in months)


 Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib & Seaborn (for visualizations)


 How It Works

1. **Data Preprocessing**
   - Handled missing values
   - Scaled features using `StandardScaler`

2. **Model Training**
   - Used Logistic Regression for binary classification

3. **Evaluation Metrics**
   - Accuracy Score
   - F1-Score
   - Confusion Matrix

4. **Prediction Output**
   - List of at-risk customers predicted as likely to churn


 Future Improvements

- Use a real-world dataset with more features
- Experiment with advanced models like Random Forest or XGBoost
- Build a web dashboard for business teams to interact with predictions


Contribution

Feel free to fork this repo and submit a pull request with enhancements or feedback!


Contact

Developed by Aman Negi  
For any questions, feel free to reach out via GitHub issues.

