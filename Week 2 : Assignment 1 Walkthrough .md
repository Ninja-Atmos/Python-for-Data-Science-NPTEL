<h1>🐍  Week 2 : Assignment 1 Walkthrough by Suvam</h1> <hr>


<h2>Q1. Which of the following object does not support indexing?</h2>
<ol>
<li>Tuple</li>
<li>List</li>
<li>Dictionary</li>
<li>Set</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">4 — Set</span>
</p>
<p><strong>Explanation:</strong><br>
Tuples and lists support indexing by position.<br>
Dictionaries support key-based access (<code>dict[key]</code>), which is a different form of indexing.<br>
Sets are unordered and do not support indexing or key-based access.</p>

<hr>

<h2>Q2. How can you concatenate the strings “data” and “science” with a hyphen (-) between them?</h2>
<ol>
<li><code>"data".join("science")</code></li>
<li><code>"-".join(["data", "science"])</code></li>
<li><code>"data" + "-" + "science"</code></li>
<li>None of the above</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">2 — "-".join(["data", "science"])</span><br>
<span style="color:green;">3 — "data" + "-" + "science"</span>
</p>
<p><strong>Explanation:</strong><br>
Option 1 joins every character of "science" with "data" in between (incorrect).<br>
Option 2 correctly joins two strings with a hyphen, producing <code>data-science</code>.<br>
Option 3 manually concatenates them with a hyphen — also correct.</p>

<hr>

<h2>Q3. What will be the output of the following code snippet?</h2>
<pre><code>import numpy as np
a = np.array([[1, 2], [3, 4]])
b = np.array([[5, 6], [7, 8]])
c = np.dot(a, b)
print(c)
</code></pre>
<ol>
<li><pre>[[ 5 12]
 [21 32]]</pre></li>
<li><pre>[[19 22]
 [43 50]]</pre></li>
<li><pre>[[ 3  8]
 [35 56]]</pre></li>
<li><pre>[[ 5 21]
 [12 32]]</pre></li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">2 — [[19 22] [43 50]]</span>
</p>
<p><strong>Explanation:</strong><br>
Matrix multiplication (<code>np.dot</code>):<br>
(1×5 + 2×7 = 19), (1×6 + 2×8 = 22),<br>
(3×5 + 4×7 = 43), (3×6 + 4×8 = 50)<br>
Result:
<pre>[[19 22]
 [43 50]]</pre></p>

<hr>

<h2>Q4. What will be the output of the following code snippet?</h2>
<pre><code>import numpy as np
a = np.arange(10)
b = a[1:5]
b[0] = 10
print(a)
</code></pre>
<ol>
<li>[1 10 3 4 5 6 7 8 9 10]</li>
<li>[10 1 2 3 4 5 6 7 8 9]</li>
<li>[0 10 2 3 4 5 6 7 8 9]</li>
<li>[10 2 3 4 5 6 7 8 9]</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">3 — [0 10 2 3 4 5 6 7 8 9]</span>
</p>
<p><strong>Explanation:</strong><br>
Slicing in NumPy returns a view, so modifying <code>b</code> changes <code>a</code>.<br>
Final array: <code>[0 10 2 3 4 5 6 7 8 9]</code></p>

<hr>

<h2>Q5. What is the output of the following code?</h2>
<pre><code>s = {1, 2, 4, 5}
l = []
for i in range(len(s)):
    l += [1 + i]
print(l)
</code></pre>
<ol>
<li>[2, 3, 4, 5]</li>
<li>[0, 1, 2, 3]</li>
<li>[1, 2, 3, 4]</li>
<li>Will throw an error: Set objects are not iterable.</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">3 — [1, 2, 3, 4]</span>
</p>
<p><strong>Explanation:</strong><br>
<code>len(s)</code> is 4, so the loop runs for i = 0..3.<br>
<code>l += [1 + i]</code> appends 1, 2, 3, 4 sequentially.<br>
The set is only used to get its length, so no iteration error occurs.</p>

<hr>

<h2>Q6. What will be the output of the following code snippet?</h2>
<ol>
<li>{27.5}</li>
<li>{1, 'four ', 3.0, 3, 5, 'two ', 10, 27.5}</li>
<li>{1, 'four ', 3.0, 5, 'two ', 10, 27.5}</li>
<li>{1, 'four ', 3.0, 5, 'two ', 3}</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">3 — {1, 'four ', 3.0, 5, 'two ', 10, 27.5}</span>
</p>
<p><strong>Explanation:</strong><br>
Python treats <code>3</code> and <code>3.0</code> as equal, so only one is stored.<br>
The resulting set keeps all other unique elements: <code>{1, 'four ', 3.0, 5, 'two ', 10, 27.5}</code>.</p>

<hr>

<h2>Q7. Let t1 = (1, 2, "tuple", 4) and t2 = (5, 6, 7). Which of the following will NOT give any error after execution?</h2>
<ol>
<li>t1.append(5)</li>
<li>x = t2[t1[1]]</li>
<li>t3 = t1 + t2</li>
<li>t3 = (t1, t2)</li>
<li>t3 = (list(t1), list(t2))</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">2 — x = t2[t1[1]]</span><br>
<span style="color:green;">3 — t3 = t1 + t2</span><br>
<span style="color:green;">4 — t3 = (t1, t2)</span><br>
<span style="color:green;">5 — t3 = (list(t1), list(t2))</span>
</p>
<p><strong>Explanation:</strong><br>
Tuples are immutable so <code>append()</code> fails.<br>
All other listed operations are valid tuple/list operations.</p>

<hr>

<h2>Q8. Let d = {1 : "Python", 2 : [1, 2, 3]}. Which among the following will NOT give an error after execution?</h2>
<ol>
<li>d[2].append(4)</li>
<li>x = d[0]</li>
<li>d["one"] = 1</li>
<li>d.update({'one': 2})</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">1 — d[2].append(4)</span><br>
<span style="color:green;">3 — d["one"] = 1</span><br>
<span style="color:green;">4 — d.update({'one': 2})</span>
</p>
<p><strong>Explanation:</strong><br>
Only <code>d[0]</code> raises KeyError (key 0 does not exist).<br>
All other statements modify dictionary/list correctly.</p>

<hr>

<h2>Q9. Which of the following data types is immutable?</h2>
<ol>
<li>list</li>
<li>set</li>
<li>tuple</li>
<li>dictionary</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">3 — tuple</span>
</p>
<p><strong>Explanation:</strong><br>
list, set, and dict are mutable.<br>
tuple is immutable.</p>

<hr>

<h2>Q10. Given:</h2>
<pre><code>student = {'name': 'Jane', 'age': 25, 'courses': ['Math', 'Statistics']}
</code></pre>
<p>Which among the following will return:</p>
<pre><code>{'name': 'Jane', 'age': 26, 'courses': ['Math', 'Statistics'], 'phone': '123-456'}
</code></pre>
<ol>
<li>student.update({'age' : 26})</li>
<li>student.update({'age' : 26, 'phone': '123-456'})</li>
<li>student['phone'] = '123-456'</li>
<li>student.update({'age' : 26})</li>
<li>None of the above</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">2 — student.update({'age' : 26, 'phone': '123-456'})</span>
</p>
<p><strong>Explanation:</strong><br>
Only option 2 updates both <code>age</code> and adds the <code>phone</code> key-value pair.</p>

<hr>

<h2>Q11. What is the output of the following code?</h2>
<pre><code>name = "Mahesh"
l = []
for i in name:
    l.append(i.capitalize())
print(l)
</code></pre>
<ol>
<li>['M', 'A', 'H', 'E', 'S', 'H']</li>
<li>['m', 'a', 'h', 'e', 's', 'h']</li>
<li>['M', 'a', 'h', 'e', 's', 'h']</li>
<li>['m', 'A', 'H', 'E', 'S', 'H']</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">1 — ['M', 'A', 'H', 'E', 'S', 'H']</span>
</p>
<p><strong>Explanation:</strong><br>
<code>.capitalize()</code> on a single character uppercases it, so all characters become uppercase.</p>

<hr>

<h2>Q12. What will be the output of the following code snippet?</h2>
<pre><code>import numpy as np
a = np.array([range(i, i+4) for i in [1, 3, 5]])
print(a)
</code></pre>
<ol>
<li>[[1 2 3 4 5]<br> [3 4 5 6 7]<br> [5 6 7 8 9]]</li>
<li>[[1 2 3 4]<br> [3 4 5 6]<br> [5 6 7 8]]</li>
<li>[[2 3 4]<br> [4 5 6]<br> [6 7 8]]</li>
<li>None of the above</li>
</ol>
<p><strong>Answer:</strong><br>
<span style="color:green;">2 — [[1 2 3 4] [3 4 5 6] [5 6 7 8]]</span>
</p>
<p><strong>Explanation:</strong><br>
List comprehension generates lists of length 4 starting from 1, 3, and 5.<br>
Creates a (3×4) NumPy array as in option 2.</p>
