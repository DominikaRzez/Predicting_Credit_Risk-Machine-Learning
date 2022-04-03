<h1>Predicting Credit Risk</h1>
<p>The following repository contains machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not.
  <br>
A training set was created from the 2019 loans and the categorical data was convereted to numeric columns by using pd.get_dummies(). Similarly, a testing set was created from the 2020 loans and the data transformation was performed accordingly. Additionally, any missing categories in the testing set were filled in to reflect the testing data.
  <br>
To compare the results two models were first created without scaling the data.
The Jupyter Notebook contains a prediction of which model (Logistic Regression or Random Forest Classifier) will perfom better and than compares the results.
  <br>
Then the training and testing sets were scaled using StandardScaler(). Another educated guess was made on how scaling will affect the accuracy of the models. Then the model scores were compared to each other, and to the previous results on unscaled data.</p>
