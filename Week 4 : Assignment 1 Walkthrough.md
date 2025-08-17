<h1>🐍 Week 4 : Assignment 1 Walkthrough by Suvam.md</h1>
<hr/>

<h2>1) Which of the following are regression problems? Assume that appropriate data is given.</h2>
<p><strong>Answers:</strong></p>
<ul>
  <li>Predicting the house price.</li>
  <li>Predicting the maximum temperature on a given day.</li>
  <li>Predicting the sales of ice creams.</li>
</ul>
<p><strong>Explanation:</strong><br>
Regression problems deal with predicting continuous numeric values. House prices, temperature, and sales are numerical quantities. Predicting if it will rain or not is a classification problem (yes/no outcome).
</p>
<hr/>

<h2>2) Which of the following are multiclass classification problems?</h2>
<p><strong>Answer:</strong></p>
<ul>
  <li>Classifying a person’s blood type as A, B, AB, or O.</li>
  <li>Classifying a movie genre into Drama, Comedy, Action, or Thriller.</li>
</ul>
<p><strong>Explanation:</strong><br>
Multiclass classification involves predicting one class from more than two categories. Blood type and movie genre have multiple categories, whereas spam/not spam is a binary classification, and predicting price is regression.
</p>
<hr/>

<h2>3) If a linear regression model achieves zero training error, can we say that all the data points lie on a straight line in the feature space?</h2>
<p><strong>Answer:</strong> Yes</p>
<p><strong>Explanation:</strong><br>
If the training error is zero, the regression line passes through every data point, meaning all points lie perfectly on a straight line (ideal case, rarely happens in real-world data).
</p>
<hr/>

<h2>4) Which of the following machine learning techniques would NOT be appropriate to solve the problem given in the problem statement?</h2>
<p><strong>Answer:</strong> Linear regression</p>
<p><strong>Explanation:</strong><br>
The task is to predict whether a car requires service or not (Yes/No), which is a classification problem. Linear regression is for continuous target variables, not categorical ones. Suitable algorithms include Logistic Regression, kNN, and Random Forest.
</p>
<hr/>

<h2>5) After applying logistic regression, what is/are the correct observations from the resultant confusion matrix?</h2>
<p><strong>Answers:</strong></p>
<ul>
  <li>True Positive = 29, True Negative = 94</li>
  <li>False Positive = 5, True Negative = 94</li>
</ul>
<p><strong>Explanation:</strong><br>
The confusion matrix shows classification outcomes. "True Positive" means correctly predicted Yes, and "True Negative" means correctly predicted No. False Positive means predicted Yes when actual is No.
</p>
<hr/>

<h2>6) The logistic regression model built between the input and output variables is checked for its prediction accuracy of the test data. What is the accuracy range (%) of the predictions made over test data?</h2>
<p><strong>Answer:</strong> 90 - 95</p>
<p><strong>Explanation:</strong><br>
Accuracy = (TP + TN) / Total × 100<br>
From the confusion matrix: TP + TN = 29 + 94 = 123. This falls in the range of 90–95%.
</p>
<hr/>

<h2>7) How are categorical variables preprocessed before model building?</h2>
<p><strong>Answer:</strong> Dummy variables</p>
<p><strong>Explanation:</strong><br>
Machine learning models require numerical inputs. Categorical variables are converted into numerical form using dummy variables (one-hot encoding).
</p>
<hr/>

<h2>8) A regression model with the function y = 80 + 4.5x was built to understand the impact of temperature x on ice cream sales y. The temperature this month is 10 degrees more than the previous month. What is the predicted difference in ice cream sales?</h2>
<p><strong>Answer:</strong> 45 units</p>
<p><strong>Explanation:</strong><br>
Δx = 10 degrees<br>
Δy = 4.5 × 10 = 45 units
</p>
<hr/>

<h2>9) X and Y are two variables that have a strong linear relationship. Which of the following statements are incorrect?</h2>
<p><strong>Answers:</strong></p>
<ul>
  <li>There cannot be a negative relationship between the two variables.</li>
  <li>The relationship between the two variables is purely causal.</li>
</ul>
<p><strong>Explanation:</strong><br>
A strong linear relationship can be positive or negative. Correlation does not imply causation; it only shows association, not a cause-effect relationship.
</p>
<hr/>

<h2>10) A multiple linear regression model is built on the Global Happiness Index dataset ‘GHI Report.csv’. What is the RMSE of the baseline model?</h2>
<p><strong>Answer:</strong> 0.50</p>
<p><strong>Explanation:</strong><br>
RMSE (Root Mean Squared Error) measures prediction error. A lower RMSE indicates better model performance. Here, 0.50 is the correct baseline RMSE.
</p>
<hr/>
