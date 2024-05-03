# Home_Credit_Default_Risk_Model_Kaggle

### Project Overview
This project aims to enhance financial inclusion by developing a predictive model that assesses the default risks associated with loan applications. Using the Home Credit Default Risk dataset from the Kaggle competition, we implemented a variety of machine learning algorithms to predict clients' repayment abilities. Our analysis focuses on clients who may struggle to obtain loans due to insufficient or nonexistent credit histories, aiming to improve their borrowing experiences through data-driven insights.

### Data Preparation and Analysis
We undertook extensive data preprocessing tasks, including handling missing values, high cardinality, and addressing class imbalance using Synthetic Minority Over-sampling Technique (SMOTE). Exploratory Data Analysis (EDA) was conducted to understand the distribution of various features and their relationship with the loan repayment difficulties.

### Modeling and Evaluation
The project tested multiple machine learning models:
- Logistic Regression
- Decision Trees
- Random Forest
- K-Nearest Neighbors
- Neural Networks

Logistic regression displayed the best performance based on ROC AUC scores, making it our model of choice. We also performed hyperparameter tuning to optimize the model further. 

### Key Insights
Our findings provide several actionable insights:
- Demographic and socio-economic factors significantly impact repayment abilities.
- Loan characteristics such as amount and type influence the likelihood of default, with cash loans showing higher default rates.
- Employment status and living arrangements are critical in predicting default risks.

### Business Impact
The project supports Home Credit's mission to provide a positive borrowing experience for underbanked populations. By identifying factors that influence repayment difficulties, we can refine lending criteria, enhance risk management, and promote financial inclusion. The predictive model developed enables Home Credit to make informed decisions about loan applications, ensuring that loans are provided to clients with manageable risk levels.

### Tools and Technologies Used
- Python for data processing and machine learning
- Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn for data manipulation and visualization
- Jupyter Notebook for development and testing

### Conclusion
This project not only demonstrates the application of data science techniques in financial risk assessment but also contributes to societal benefits by aiding in financial inclusion. By understanding and predicting default risks, we can help more individuals access the financial support they need without compromising on the safety and soundness of lending practices.

