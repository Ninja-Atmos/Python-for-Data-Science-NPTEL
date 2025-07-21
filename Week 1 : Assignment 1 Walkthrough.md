<h1>🐍 Week 1 : Assignment 1 Walkthrough by Suvam</h1>
<!-- <hr> -->

<h2>1️⃣ Which of the following variable names are INVALID in Python?</h2>

<p><strong>Options:</strong></p>
<ol>
<li><code>1_variable</code></li>
<li><code>variable_1</code></li>
<li><code>variable1</code></li>
<li><code>variable#</code></li>
</ol>

<p>✅ <strong>Selected Answers:</strong> 1, 4</p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li>Variables cannot start with a digit (<code>1_variable</code> is invalid).</li>
<li>Variables cannot contain special characters other than <code>_</code> (<code>variable#</code> is invalid).</li>
<li><code>variable_1</code> and <code>variable1</code> are valid.</li>
</ul>

<hr>

<h2>2️⃣ Which of the following operators have lower precedence than <code>not</code> in Python?</h2>

<p><strong>Options:</strong></p>
<ol>
<li><code>+</code></li>
<li><code>and</code></li>
<li><code>==</code></li>
<li><code>|</code></li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 2. <code>and</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li><code>and</code> has lower precedence than <code>not</code>.</li>
<li>All others have higher precedence.</li>
</ul>

<hr>

<h2>3️⃣ What will be the output of the following code?</h2>

<pre><code>a = 10
b = 5
print(a * b % 3)</code></pre>

<p><strong>Options:</strong></p>
<ol>
<li>0</li>
<li>100</li>
<li>1</li>
<li>2</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 3. <code>1</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li>10 × 5 = 50</li>
<li>50 % 3 = 1</li>
<li>Output: <code>1</code></li>
</ul>

<hr>

<h2>4️⃣ What will be the output of the following code snippet?</h2>

<pre><code>greetings = "Namaste"
greetings_1 = float(greetings)
print(type(greetings_1))</code></pre>

<p><strong>Options:</strong></p>
<ol>
<li>int</li>
<li>float</li>
<li>str</li>
<li>Code will throw an error.</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 4. <code>Code will throw an error.</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li>Cannot convert non-numeric string <code>"Namaste"</code> to <code>float</code>. Raises <code>ValueError</code>.</li>
</ul>

<hr>

<h2>5️⃣ Given <code>j = 6</code> and <code>g = 3.3</code>, what would be the data type of the value obtained from normal division and floor division (<code>j / g</code> and <code>j // g</code>)?</h2>

<p><strong>Options:</strong></p>
<ol>
<li>int, int</li>
<li>float, float</li>
<li>float, int</li>
<li>int, float</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 2. <code>float, float</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li><code>j / g</code> → float</li>
<li><code>j // g</code> → float (since one operand is float)</li>
</ul>

<hr>

<h2>6️⃣ What will be the output of the following code snippet?</h2>

<pre><code>a = "10"
b = float(a) + 5
result = str(b) + "123"
print(type(result))</code></pre>

<p><strong>Options:</strong></p>
<ol>
<li>&lt;class 'float'&gt;</li>
<li>&lt;class 'str'&gt;</li>
<li>&lt;class 'int'&gt;</li>
<li>The code will give an error.</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 2. <code>&lt;class 'str'&gt;</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li><code>result</code> is a string: <code>"15.0123"</code></li>
</ul>

<hr>

<h2>7️⃣ What will be the output of the following code snippet?</h2>

<pre><code>a = 15
b = 3
c = 4
result = a + b * c // (c % b) - 5
print(result)</code></pre>

<p><strong>Options:</strong></p>
<ol>
<li>20</li>
<li>1</li>
<li>22</li>
<li>0</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 3. <code>22</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li><code>c % b = 1</code></li>
<li><code>b * c = 12</code></li>
<li><code>12 // 1 = 12</code></li>
<li><code>15 + 12 - 5 = 22</code></li>
</ul>

<hr>

<h2>8️⃣ What is the output of the following code snippet?</h2>

<pre><code>a = 4
b = 5
a *= b * 2
print(a)</code></pre>

<p><strong>Options:</strong></p>
<ol>
<li>10</li>
<li>20</li>
<li>25</li>
<li>40</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 4. <code>40</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li><code>b * 2 = 10</code></li>
<li><code>a *= 10 → 4 * 10 = 40</code></li>
</ul>

<hr>

<h2>9️⃣ What is the output of the following code snippet?</h2>

<pre><code>a = 3
b = 5
c = (a == 3) and (b == 5) or (a != 3)
print(c)</code></pre>

<p><strong>Options:</strong></p>
<ol>
<li>True</li>
<li>False</li>
<li>Error</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 1. <code>True</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li><code>(a == 3) and (b == 5)</code> → True</li>
<li><code>(a != 3)</code> → False</li>
<li><code>True or False → True</code></li>
</ul>

<hr>

<h2>🔟 Let <code>a = 5 (101)</code> and <code>b = 3 (011)</code> in binary. What is the result of the following operation?</h2>

<pre><code>a = 5
b = 3
print(a & b)</code></pre>

<p><strong>Options:</strong></p>
<ol>
<li>3</li>
<li>7</li>
<li>5</li>
<li>1</li>
</ol>

<p>✅ <strong>Selected Answer:</strong> 4. <code>1</code></p>

<p>💡 <strong>Explanation:</strong></p>
<ul>
<li>Binary <code>101 & 011 = 001</code> → <code>1</code></li>
</ul>

<hr>
