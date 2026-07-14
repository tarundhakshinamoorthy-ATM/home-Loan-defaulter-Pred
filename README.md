Developed an end-to-end machine learning solution to predict whether a customer is likely to default on a home loan. The project involved integrating seven financial datasets, performing comprehensive exploratory data analysis (EDA), handling missing values, engineering customer-level features, and building predictive models for credit risk assessment.

Several machine learning algorithms, including Logistic Regression, Balanced Logistic Regression, Random Forest, and XGBoost, were trained and evaluated using Accuracy, Precision, Recall, F1-Score, and ROC-AUC. XGBoost with an optimized decision threshold was selected as the final production model, achieving a ROC-AUC of 0.781 while improving the identification of potential defaulters.

Key Highlights
Integrated and merged 7 relational financial datasets into a unified customer-level dataset.
Performed extensive EDA, missing value treatment, feature engineering, and preprocessing.
Engineered 70+ meaningful features from customer credit history, installment payments, previous applications, POS transactions, and credit card behavior.
Addressed class imbalance using Balanced Logistic Regression, class-weighted Random Forest, and threshold optimization for XGBoost.
Evaluated multiple models and selected the best production model based on business-oriented performance metrics.
Saved the final XGBoost model for future deployment using Python Pickle.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Pickle
Jupyter Notebook
Results
Best Model: XGBoost (Optimized Threshold)
ROC-AUC: 0.781
Successfully improved loan default detection while maintaining strong overall classification performance.
