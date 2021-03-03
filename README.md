# Bank_Churners_Prediction
- The purpose of this project is to predict whether bank customers will churn using multiple machine learning models. 
- I achieved the best results using the Gradient Boost model. To improve the accuracy I used the SMOTE technique to upsample the imbalanced target class.

- My final model achieved an accuracy of 97.2% and a standard deviation of 0.69% with 10 K-Folds.
- Of the 331 who did actually churn, my model was able to correctly identify 269 of them for an accuracy of 81%.


### Credits
Download the dataset here: https://www.kaggle.com/sakshigoyal7/credit-card-customers

----



### Breakdown

#### Data Cleaning
- Drop unneccssary rows from dataframe

#### Data Visualization/Exploration
- Histograms to visualize distribution of continuous features 
- Bar Charts to visualize categorical features
- Heat Map to show correlation between features
- Pie Chart to visualize target variable
- Bar Chart to show correlation between features and the target variable

#### Data Processing
- Log Transform Non-normally Distributed Numerical Columns (i.e. credit limit)
- Encode Binary Columns
- Encode Categorical Features with One-Hot Encoding 
- Split data into the training set and test set
- Feature Scale using Min-Max Scaler

#### Model Selection
- Trained Logistic Regression, KNN, SVM, Kernel SVM, Naive Bayes, Decision Tree, Random Forest, and XGBoost models on the training set
- Evaluated the models on the test set
- Achieved the highest accuracy with XGBoost

#### Model Improvement
- Used SMOTE to upsample the imbalanced target class and retrain our model

#### Final Results
- The Final XGBoost model achieved an overall accuracy of 97.2% and a standard deviation of 0.69% with 10 K-Folds.
- Of the 331 people who did actually churn, our model was able to correcly identify 269 of them for an accuracy (recall of class 1) of 81%.
