<h1>🐍 Week 2: Practice Assignment 1 Walkthrough by Suvam</h1>
<hr>

<h2>📘 Question 1</h2>

<pre>
Variable <code>a</code> is defined as:

a = 'gOOd moRning'

What is the command to convert 'a' from 'gOOd moRning' to 'Good Morning'?
</pre>

<b>Options:</b><br>
1. a.upper( )<br>
2. a.lower( )<br>
3. a.string( )<br>
4. a.title( )<br>

<b>✅ Answer: 4 - a.title()</b><br>
<b>Explanation:</b> <code>.title()</code> capitalizes the first letter of each word and lowers the rest.  
Output: <code>'Good Morning'</code>

---

<h2>📘 Question 2</h2>

<pre>
Create a list called Stationery:

Product = ['Pencil', 'Pen', 'Eraser', 'Pencil Box', 'Scale']  
Price = [5, 10, 2, 20, 12]  
Brand = ['Camlin', 'Rotomac', 'Nataraj', 'Camel', 'Apsara']  
Stationery = [Product, Price, Brand]

What is the command to add "Notebook" as the first element in the first list inside Stationery?
</pre>

<b>Options:</b><br>
1. Stationery[0].append('Notebook')<br>
2. Stationery[0].insert(0, 'Notebook')<br>
3. Stationery[0][1] = 'Notebook'<br>
4. Stationery[0].extend('Notebook')<br>

<b>✅ Answer: 2 - Stationery[0].insert(0, 'Notebook')</b><br>
<b>Explanation:</b> <code>.insert(0, ...)</code> adds to the beginning of the list.  
<code>append()</code> adds to the end, <code>extend()</code> adds characters individually, and option 3 replaces `'Pen'`.

---

<h2>📘 Question 3</h2>

<pre>
The method to clear all the elements from a Set is:
</pre>

<b>Options:</b><br>
1. remove( )<br>
2. discard( )<br>
3. clear( )<br>
4. delete( )<br>

<b>✅ Answer: 3 - clear()</b><br>
<b>Explanation:</b> <code>clear()</code> removes all items from a set.  
<code>remove()</code> and <code>discard()</code> remove individual items. <code>delete()</code> is not a valid method.

---

<h2>📘 Question 4</h2>

<pre>
Given the list:

Mylist = ['a', 'a', 'b', 'b', 'b', 'c', 'c', 'd', 'e']

What is the output of:
Mylist.index('d')
</pre>

<b>Options:</b><br>
1. 7<br>
2. 8<br>
3. 4<br>
4. 6<br>

<b>✅ Answer: 1 - 7</b><br>
<b>Explanation:</b> The <code>.index('d')</code> method returns the index of the first occurrence of `'d'`, which is 7.

---

<h2>📘 Question 5</h2>

<pre>
Which of the following Python sequence data types is immutable?
</pre>

<b>Options:</b><br>
1. list<br>
2. dictionary<br>
3. tuple<br>
4. array<br>

<b>✅ Answer: 3 - tuple</b><br>
<b>Explanation:</b> Only <code>tuple</code> is immutable.  
<code>list</code>, <code>dictionary</code>, and <code>array</code> are mutable.

---

