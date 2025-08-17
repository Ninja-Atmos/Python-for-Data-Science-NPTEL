<h1>🐍 Week 4: Practice Assignment 1 Walkthrough by Suvam</h1>
<hr/>

<h2>1) Which of the following functions can be used to split the data into train and test?</h2>
<ol type="1">
  <li>pandas.train_test_split()</li>
  <li>numpy.train_test_split()</li>
  <li>sklearn.model_selection.train_test_split()</li>
  <li>sklearn.train_test_split()</li>
</ol>
<p><strong>Answer:</strong> 3. sklearn.model_selection.train_test_split()</p>
<p><strong>Explanation:</strong><br>
The function <code>train_test_split()</code> from <code>sklearn.model_selection</code> is the correct way to split datasets into training and testing sets in scikit-learn. Pandas and NumPy do not provide this function directly.
</p>
<hr/>

<h2>2) The function used to perform k-Nearest Neighbors classification is:</h2>
<ol type="1">
  <li>sklearn.KNN</li>
  <li>sklearn.KNearestClassifier</li>
  <li>sklearn.neighbors.KNeighborsClassifier()</li>
  <li>sklearn.neighbors.KNeighborsRegressor()</li>
</ol>
<p><strong>Answer:</strong> 3. sklearn.neighbors.KNeighborsClassifier()</p>
<p><strong>Explanation:</strong><br>
<code>KNeighborsClassifier</code> is used for classification tasks. <code>KNeighborsRegressor</code> is for regression tasks.
</p>
<hr/>

<h2>3) A Linear Regression model is said to be good when the R-squared value tends to:</h2>
<ol type="1">
  <li>0</li>
  <li>1</li>
  <li>-1</li>
  <li>0.5</li>
</ol>
<p><strong>Answer:</strong> 2. 1</p>
<p><strong>Explanation:</strong><br>
The closer the R-squared value is to 1, the better the model fits the data.
</p>
<hr/>

<h2>4) The Gini coefficient ranges from:</h2>
<ol type="1">
  <li>0 to 1</li>
  <li>-1 to 0</li>
  <li>-1 to 1</li>
  <li>None of the above</li>
</ol>
<p><strong>Answer:</strong> 1. 0 to 1</p>
<p><strong>Explanation:</strong><br>
The Gini coefficient is a measure of inequality or impurity, with values between 0 (perfect equality) and 1 (maximum inequality).
</p>
<hr/>

<h2>5) What is heteroscedasticity as used to assess a Linear Regression model?</h2>
<ol type="1">
  <li>Linear regression with varying error terms</li>
  <li>Linear regression with constant error terms</li>
  <li>Linear regression with no error terms</li>
  <li>All the above</li>
</ol>
<p><strong>Answer:</strong> 1. Linear regression with varying error terms</p>
<p><strong>Explanation:</strong><br>
Heteroscedasticity occurs when the variance of residuals is not constant across the range of predictors, violating a key assumption of linear regression.
</p>
<hr/>
