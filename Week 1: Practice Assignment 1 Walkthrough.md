<h1>🐍 Week 1: Practice Assignment 1 Walkthrough by Suvam</h1>

<h3>1️⃣ Which of the following is a valid variable name?</h3>
<ul>
<li>1. .ram2</li>
<li>2. ram.2</li>
<li>3. ram_2</li>
<li>4. 2ram00</li>
</ul>
<p>✅ <strong>Selected Answer:</strong> 3. ram_2</p>
<p>💡 <strong>Explanation:</strong></p>
<p>Variable names cannot start with a digit (2ram00 invalid).<br>
Variable names cannot contain <code>.</code> or start with <code>.</code> (.ram2, ram.2 invalid).<br>
Underscore <code>_</code> is allowed, so ram_2 is valid.</p>

<h3>2️⃣ Which of the following statement is invalid?</h3>
<ul>
<li>1. m_n_q = 3500</li>
<li>2. m.n.q = 3500, 3600, 3700</li>
<li>3. m,n,q = 3500, 3600, 3700</li>
<li>4. mnq = 350036003700</li>
</ul>
<p>✅ <strong>Selected Answer:</strong> 2. m.n.q = 3500, 3600, 3700</p>
<p>💡 <strong>Explanation:</strong></p>
<p>m.n.q is invalid because dots <code>.</code> are not allowed in variable names.<br>
Other assignments are all valid.</p>

<h3>3️⃣ Assignment operator used in Python is:</h3>
<ul>
<li>1. ==</li>
<li>2. >></li>
<li>3. <-</li>
<li>4. =</li>
</ul>
<p>✅ <strong>Selected Answer:</strong> 4. =</p>
<p>💡 <strong>Explanation:</strong></p>
<p><code>=</code> is the assignment operator.<br>
<code>==</code> is comparison, <code>>></code> is bitwise shift, <code><-</code> is not valid in Python.</p>

<h3>4️⃣ Which command would you use to find the data type of a variable?</h3>
<ul>
<li>1. data()</li>
<li>2. type()</li>
<li>3. typeof()</li>
<li>4. str()</li>
</ul>
<p>✅ <strong>Selected Answer:</strong> 2. type()</p>
<p>💡 <strong>Explanation:</strong></p>
<p><code>type(variable)</code> returns the type of the variable.<br>
<code>data()</code>, <code>typeof()</code> are not defined in Python.<br>
<code>str()</code> converts to string, it doesn’t check type.</p>

<h3>5️⃣ What will be the output after the following statements are executed?</h3>
<pre><code>X = 300 
Y = 17
X %= Y
print(X)
</code></pre>
<ul>
<li>1. 11</li>
<li>2. 17.6</li>
<li>3. 300</li>
<li>4. 17</li>
</ul>
<p>✅ <strong>Selected Answer:</strong> 1. 11</p>
<p>💡 <strong>Explanation:</strong></p>
<p>300 % 17 = 11<br>
Then <code>X %= Y</code> updates <code>X</code> to 11.<br>
Output: 11</p>
