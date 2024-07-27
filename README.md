### Project Overview 
The main objective of the Bank 
Customer Churn Prediction project is to analyze the demographics and financial information of bank customers, including factors like age, gender, credit score, country, balance, and more, in order to predict whether a customer will leave the bank or not. Customer churn, the decision of customers to leave a bank, can significantly impact the bank's business and profitability. By accurately predicting customer churn, the bank can take proactive measures to retain valuable customers and enhance customer satisfaction.

## Data Preprocessing

1. Data Cleaning: Removed superfluous columns to streamline the dataset.
2. Data Visualization: Conducted exploratory data analysis to gain insights into the dataset's characteristics.
3. Data Standardization: Normalized numerical features to ensure consistent scale across variables.
4. Categorical Encoding: Implemented label encoding for categorical variables to prepare them for machine learning algorithms.

## Model Performance Enhancement

Initially, the model's performance was suboptimal. To address this issue, we implemented the ADASYN (Adaptive Synthetic) sampling technique.

### ADASYN Implementation

By employing the ADASYN method, we significantly increased the number of samples for minority classes. This resampling technique led to a substantial enhancement in the model's predictive accuracy. The rebalanced dataset resulted in improved performance in predicting fraudulent warranty claims.

## Key Findings

1. ADASYN effectively addressed the class imbalance problem in our dataset.
2. The balanced data led to a more robust and accurate prediction model.
3. The model's ability to identify fraudulent warranty claims improved considerably.

## Conclusion

These findings demonstrate that utilizing class balancing techniques like ADASYN can significantly enhance the performance of fraud prediction models. We recommend employing ADASYN and machine learning models trained using this method for analyzing and predicting warranty claims fraud, as it can lead to improved accuracy and predictive capability of the models.

## Developer Information

*Developed by Hosein Mohammadi*

GitHub : https://github.com/Hosein541

LinkedIn : https://www.linkedin.com/in/hosein-mohammadi-979b8a2b2/

Gmail : Huseinmohammadi83@gmail.com
