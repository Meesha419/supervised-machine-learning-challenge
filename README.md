# supervised-machine-learning-challenge

**Retrieve Data**
* Import the lending_data.csv file as a Pandas dataframe 
- Confirm that the import was successful by displaying the dataframe 

**Predict Model Performance**

* Make a prediction on which model will perform better on the data 
- Justify the prediction with information about the models 

**Split the Data into Training and Testing Sets**

* Create the features DataFrame, X, by removing the loan_status column 
+ Create y, the labels set, by using the loan_status column 
- Split the data into training and testing datasets by using the train_test_split function 

**Create, Fit and Compare Models**

* Create and train a Logistic Regression model 
- Score the Logistic Regression model 
+ Create and train a Random Forest Classifier model 
* Score a Random Forest Classifier model 
- State which model performed better 
+ Compare the actual model performance with your predictions 



## ***Prediction*** ##

I am predicting the Logistic Regression would do better with the dataset we are modelling to check whether a loan can be approved or not (Credit Risk).

My prediction is based on 'LogisticsRegression' doing better with categorical data than 'Random Forrest Classifiers' even though RandomTrees can handle both categorical and numerical variables.

I predict the Logistic Regression will do better than Random Forest on scaled data as well.
##  ##

**Before scaling the data**

*	LogisticRegression Training score: 0.9921240885954051
-	LogisticRegression Test score: 0.9918489475856377
+	RandomForestClassifier Training score: 0.9975409272252029
* RandomForestClassifier Test score: 0.9914878250103177

**After scaling the data**
*	Scaled LogisticRegression Training score: 0.9942908240473243
-	Scaled LogisticRegression Test score: 0.9936545604622369
+	Scaled RandomForestClassifier Training score: 0.9975409272252029
*	Scaled RandomForestClassifier Test score: 0.9915910028889806


>The test and training scores are very similar.
>After creating a "Confusion Matrix" for both "Test Data Models" it is clear, when you look at the "Acuracy Scores" that both models carry out well on the dataset.   

