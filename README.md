# Banking-Customer-Churn-Prediction

_COMPANY_: CODTECH IT SOLUTIONS

_NAME_: AARTHI N

_INTERN ID_: CT04DY248

_DOMAIN_: DATA ANALYTICS

_DURATION_: 4 WEEKS

_MENTOR_: NEELAM SANTOSH

**PROJECT DESCRIPTION**:

The **Customer Churn Prediction** project is an end-to-end data science and machine learning application designed to identify customers who are likely to leave a business. This type of predicitive modelling is essential for organisations such as banks, telecom companies, and subscription-based businesses, as retaining customers is more cost-effective than acquiring new ones.

**TOOLS & LIBRARIES USED**:

The project was implemented using Python in a Jupyter Notebook environment. Several key python libraries were used:

  * **Pandas**: for data loading, cleaning and manipulation. It helped in handling the CSV dataset and performing tabular operations.
  * **Numpy**: used for numerical computations, array operations and statistical analysis.
  * **Matplotlib & Seaborn**: for data visualization and exploratory data analysis (EDA). They help in plotting churn distribution, feature correlations and customer behaviour trends.
  * **Scikit-learn (sklearn)**: for machine-learning tasks, including train-test splitting, feature scaling, model training, and evaluation. Models such as Logistic Regression, Random Forest have been applied.
  * **Other ML utilities**: StandardScaler, LabelEncoder and evaluation metrics such as accuracy, precision, recall, F1-score, and ROC_AUC.

**METHODOLOGY AND WORKFLOW**:

1. **Data Collection and Loading**:

   The dataset Churn_modelling.csv was loaded into the notebook using pandas. It contains customer information such as demographics, account balance, tenure, credit score, number of products and whether the customer exited (churned).

2. **Exploratory Data Analysis**:

   Initial exploration included examining the dataset's shape, column information, statistical summaries and null value checks. Visualizations were created to study the distribution of churned vs non-churned customers, categorical feature behaviour, and numerical variables. Outliers were also analyzed by calculating churn ratios and fractions.

3. **Data Preprocessing and Feature Engineering**:

   Since machine-learning models work better with numerical features, categorical variables (like geography and gender) were encoded using **One-hot encoding** or **Label encoding**. Continuous variables such as balance and age were normalized or standardized using **StandardScaler**. Additionally, unnecessary columns were dropped to prevent bias.

4. **Model Building**:

   The dataset was split into training and testing sets. Different machine-learning algorithms were then applied such as Logistic Regression, Decision trees, Random Forest, and Gradient Boosting. Each model was trained on the training set and evaluated on the test set.

5. **Model Evaluation**:

   To measure effectiveness, multiple evaluation metrics were used. Since churn prediction is a classification problem, accuracy alone may not suffice. Therefore, precision, recall, F1-score, and ROC-AUC were considered. The recall metric was emphasized more, as businesses prefer identifying potential churners even at the cost of some false positives.

6. **Result interpretation and insights**:

     The final step involved analyzing which features contributed most to customer churn. For example, tenure, balance and the number of products are often critical indicators. Visualizations such as feature importance plots were generated to interpret model results.

**Conclusion**:

This project demonstrates how machine-learning can be applied to a real-world business problem of **customer retention**. By leveraging Python, Jupyter notebook and some libraries like Pandas, Numpy and Scikit-learn, the project sucessfully builds an analytical pipeline that goes from raw data to actionable insights. The model not only predicts whether a customer is likely to churn but also helps businesses understanding the driving factors, enabling them to take preventive actions such as targeted marketing campaigns or personalized customer engagement strategies.
