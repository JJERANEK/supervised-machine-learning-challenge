# Supervised Machine Learning Challenge
<img src="Supervised_Machine_Learning_Challenge/Resources/AI.png" width="1000" height="500">
<br>
This is an assignment for the University of Minnesota Data Analytics and Visualization Boot Camp.
<br>

# Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.
<br>

# Prediction
At the start of the assignment, I predicted that the Random Forest Classifier would perform better for this dataset than the Logistic Regression. The reasoning I used is that the Random Forest Classifier is meant to predict the classification of an object, and a Logistic Regression will give a probability of the object falling into a certain category, but it will not predict the exact category.
<br>

# Creating the Models
Both models would use "loan_status" as y with the other columns representing X. Data was split into training and testing datasets using the train_test_split function. The models were then created and fit to the training data. Scores were calculated for both models.
<br>

# Results
## *Random Forest Classifier*<br>
Training Score: 0.9921240885954051<br>
Testing Score: 0.9918489475856377
<br>

## *Logistic Regression*<br>
Training Score: 0.9974893382858715<br>
Testing Score: 0.9910235245563351
<br>
<br>

### *Which model performed better?*
While both models performed quite accurately, the Logistic Regression model performed better with the testing data, though the training data score wasn't as good as the Random Forest Classifier's training data score. In this case, using the Logistic Regression would be appropriate. This is the opposite of what I predicted, though I thought there would be a much larger divide in performance than there actually was.