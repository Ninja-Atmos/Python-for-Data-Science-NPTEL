<h1>🐍 Week 3: Assignment 1 Walkthrough by Suvam</h1>

<hr>

<h2> 1. Which of the following is the correct approach to fill missing values in case of categorical variable?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>Mean</li>
  <li>Median</li>
  <li>Mode</li>
  <li>None of the above</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 3. Mode</p>
<p>💡 <strong>Explanation:</strong> Mode is the most frequent category and best suited for filling missing categorical data.</p>

<hr>

<h2> 2. Which of the following can be used to extract the column Type as a separate dataframe?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>df_cars[[‘Type’]]</li>
  <li>df_cars.iloc[[:, 1]</li>
  <li>df_cars.loc[:, [‘Type’]]</li>
  <li>None of the above</li>
</ol>
<p>✅ <strong>Selected Answers:</strong> 1. df_cars[[‘Type’]], 3. df_cars.loc[:, [‘Type’]]</p>
<p>💡 <strong>Explanation:</strong> Both methods correctly extract the column "Type" as a DataFrame.</p>

<hr>

<h2> 3. The method df_cars.describe() will give description of which column?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>Car name</li>
  <li>Brand</li>
  <li>Price (in lakhs)</li>
  <li>All of the above</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 3. Price (in lakhs)</p>
<p>💡 <strong>Explanation:</strong> describe() provides summary statistics for numeric columns only.</p>

<hr>

<h2> 4. Which pandas function is used to stack the dataframes vertically?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>pd.merge()</li>
  <li>pd.concat()</li>
  <li>join()</li>
  <li>None of the above</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 2. pd.concat()</p>
<p>💡 <strong>Explanation:</strong> pd.concat() is used for vertical or horizontal stacking of DataFrames.</p>

<hr>

<h2> 5. Which of the following are libraries in Python?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>NumPy</li>
  <li>All of the above</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 4. All of the above</p>
<p>💡 <strong>Explanation:</strong> All three are popular Python libraries used in data analysis and visualization.</p>

<hr>

<h2> 6. Which of the following variables have null values?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>ID</li>
  <li>Company</li>
  <li>Review Date</li>
  <li>Rating</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 3. Review Date</p>
<p>💡 <strong>Explanation:</strong> Based on the dataset, the 'Review Date' column contains null values.</p>
<p>📁 Dataset: <a href="https://drive.google.com/file/d/1Oeq1sG3k72OXABY2e89HYJQr7QFcY-Ke/view?usp=drive_link" target="_blank">flavors_of_cocoa.csv</a></p>

<hr>

<h2> 7. Which of the following countries have maximum locations of cocoa manufacturing companies?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>U.K.</li>
  <li>U.S.A.</li>
  <li>Canada</li>
  <li>France</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 2. U.S.A.</p>
<p>💡 <strong>Explanation:</strong> From data analysis, U.S.A. has the highest number of cocoa company locations.</p>

<hr>

<h2> 8. After checking the data summary, which feature requires a data conversion?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>Rating</li>
  <li>Review Date</li>
  <li>Company</li>
  <li>Bean origin</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 2. Review Date</p>
<p>💡 <strong>Explanation:</strong> Review Date should be converted from numeric to datetime type for accurate analysis.</p>

<hr>

<h2> 9. What is the maximum rating of chocolates?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>1.00</li>
  <li>5.00</li>
  <li>3.18</li>
  <li>4.00</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 2. 5.00</p>
<p>💡 <strong>Explanation:</strong> Maximum value in the Rating column is 5.0.</p>

<hr>

<h2> 10. What will be the output of the following code?</h2>
<pre><code>import numpy as np
B = [True, 2, 3.0, np.nan, "False"]
[type(i) for i in B]</code></pre>
<p><strong>Options:</strong></p>
<ol>
  <li>[bool, int, float, float, str]</li>
  <li>[str, int, float, float, str]</li>
  <li>[bool, int, float, int, str]</li>
  <li>[bool, int, int, float, str]</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 1. [bool, int, float, float, str]</p>
<p>💡 <strong>Explanation:</strong> The types are detected as bool, int, float, float (for np.nan), and str.</p>

<hr>

<h2> 11. What does df.info() provide?</h2>
<p><strong>Options:</strong></p>
<ol>
  <li>Summary of the DataFrame, including the number of non-null entries.</li>
  <li>The first 5 rows of the DataFrame</li>
  <li>The data types of the columns</li>
  <li>The correlation matrix of the DataFrame</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 1. Summary of the DataFrame, including the number of non-null entries.</p>
<p>💡 <strong>Explanation:</strong> df.info() provides the number of non-null entries, column names, and data types.</p>

<hr>

<h2> 12. What will be the output of the following code?</h2>
<pre><code>import numpy as np
arr = np.array([1, 2, 3, 4, 5])
print(arr[::2])</code></pre>
<p><strong>Options:</strong></p>
<ol>
  <li>[1, 2]</li>
  <li>[1, 3, 5]</li>
  <li>[1, 2, 3, 4, 5]</li>
  <li>[5, 4, 3, 2, 1]</li>
</ol>
<p>✅ <strong>Selected Answer:</strong> 2. [1, 3, 5]</p>
<p>💡 <strong>Explanation:</strong> The slicing <code>arr[::2]</code> selects every second element from the beginning of the array.</p>

<hr>
