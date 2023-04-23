<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
  
  </head>
  <body>
    <h2> Keywords </h2>
    <p>In Python, keywords are reserved words that have a specific meaning and purpose in the language. These words cannot be used as variable names, function names, or any other identifiers.</p>
    <p>There are 35 keywords in Python 3.10:</p>
     <table>
      <tbody>
        <tr>
          <td>False</td>
          <td>await</td>
          <td>else</td>
          <td>import</td>
          <td>pass</td>
        </tr>
        <tr>
          <td>None</td>
          <td>break</td>
          <td>except</td>
          <td>in</td>
          <td>raise</td>
        </tr>
        <tr>
          <td>True</td>
          <td>class</td>
          <td>finally</td>
          <td>is</td>
          <td>return</td>
        </tr>
        <tr>
          <td>and</td>
          <td>continue</td>
          <td>for</td>
          <td>lambda</td>
          <td>try</td>
        </tr>
        <tr>
          <td>as</td>
          <td>def</td>
          <td>from</td>
          <td>nonlocal</td>
          <td>while</td>
        </tr>
        <tr>
          <td>assert</td>
          <td>del</td>
          <td>global</td>
          <td>not</td>
          <td>with</td>
        </tr>
        <tr>
          <td>async</td>
          <td>elif</td>
          <td>if</td>
          <td>or</td>
          <td>yield</td>
        </tr>
      </tbody>
    </table>

<br><h3>The above keywords ⬆️ </h3> <p> may get altered in different versions of Python. Some extra might get added or some might be removed. You can always get the list of keywords in your current version by typing the following in the prompt:</p>

<pre>
&gt;&gt;&gt; import keyword
&gt;&gt;&gt; print(keyword.kwlist)
['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
</pre>

	  
	  
<br>
<h3> We will cover these keywords later on when we learn about data types, variables, and control structures in Python. </h3>
<br>h3> here's a brief overview of what each Python keyword does:</h3>
<table>
		<tr>
			<th>Keyword</th>
			<th>Description</th>
		</tr>
		<tr>
			<td>False</td>
			<td>A boolean value that represents false.</td>
		</tr>
		<tr>
			<td>None</td>
			<td>A value that represents null or no value.</td>
		</tr>
		<tr>
			<td>True</td>
			<td>A boolean value that represents true.</td>
		</tr>
		<tr>
			<td>and</td>
			<td>A logical operator that performs a logical "and" operation between two boolean values or expressions.</td>
		</tr>
		<tr>
			<td>as</td>
			<td>Used for aliasing or renaming a module, function, or class.</td>
		</tr>
		<tr>
			<td>assert</td>
			<td>Used for debugging purposes to check whether a condition is true or not. Raises an AssertionError if the condition is false.</td>
		</tr>
		<tr>
			<td>async</td>
			<td>Used to declare a coroutine function that returns an asynchronous generator or an asynchronous iterator.</td>
		</tr>
		<tr>
			<td>await</td>
			<td>Used inside an async function to wait for a coroutine to complete before moving on to the next statement.</td>
		</tr>
		<tr>
			<td>break</td>
			<td>Used to exit out of a loop (for, while, or do-while) prematurely.</td>
		</tr>
		<tr>
			<td>class</td>
			<td>Used to define a new class.</td>
		</tr>
		<tr>
			<td>continue</td>
			<td>Used to skip the current iteration of a loop and move on to the next one.</td>
		</tr>
		<tr>
			<td>def</td>
			<td>Used to define a new function or method.</td>
		</tr>
		<tr>
			<td>del</td>
			<td>Used to delete a variable, object, or attribute.</td>
		</tr>
		<tr>
			<td>elif</td>
			<td>Short for "else if", used in conditional statements to test multiple conditions.</td>
		</tr>
		<tr>
			<td>else</td>
			<td>Used in conditional statements to execute a block of code when none of the previous conditions are true.</td>
		</tr>
		<tr>
			<td>except</td>
			<td>Used in try-except blocks to handle exceptions.</td>
		</tr>
		<tr>
			<td>finally</td>
            <td>Used in try-except blocks to execute a block of code regardless of whether an exception is raised or not.</td>
        </tr>
        <tr>
			<td>for</td>
            <td>Used to iterate over a sequence (such as a list, tuple, or string) or other iterable objects.</td>
        </tr>
        <tr>
			<td>from</td>
            <td>Used to import specific functions, classes, or variables from a module.</td>
        </tr>
        <tr>
			<td>global</td>
            <td>Used to declare a variable as global, allowing it to be accessed from anywhere in the program.</td>
        </tr>
        <tr>
			<td>if</td>
            <td>Used in conditional statements to test a condition.</td>
        </tr>
        <tr>
			<td>import</td>
            <td>Used to import a module into the current program.</td>
        </tr>
        <tr>
			<td>in</td>
            <td>Used to test if a value is a member of a sequence or iterable object. </td>
        </tr>
        <tr>
			<td>is</td>
            <td>Used to test if two objects are the same object (i.e., have the same identity).</td>
        </tr>
        <tr>
			<td>lambda</td>
            <td>Used to define an anonymous (or "inline") function.</td>
        </tr>
        <tr>
			<td>nonlocal</td>
            <td>Used to declare a variable as non-local, allowing it to be accessed from nested functions or scopes.</td>
        </tr>
        <tr>
			<td>not</td>
            <td>A logical operator that performs a logical "not" operation on a boolean value or expression.</td>
        </tr>
        <tr>
			<td>or</td>
            <td>A logical operator that performs a logical "or" operation between two boolean values or expressions.</td>
        </tr>
        <tr>
			<td>pass</td>
            <td>A null statement that does nothing. Used as a placeholder in code that requires a statement.</td>
        </tr>
        <tr>
			<td>raise</td>
            <td>Used to raise an exception.</td>
        </tr>
        <tr>
			<td>return</td>
            <td>Used to return a value from a function or method.</td>
        </tr>
        <tr>
			<td>try</td>
            <td>Used to test a block of code for exceptions.</td>
        </tr>
        <tr>
			<td>while</td>
            <td>Used to create a loop that executes as long as a condition is true.
            </td>
        </tr>
        <tr>
			<td>with</td>
            <td>Used to simplify exception handling and resource management by automatically closing a file or database connection.</td>
        </tr>
        <tr>
			<td>yield</td>
            <td>Used inside a function to return a generator object that can be iterated over.</td>
        </tr>




        



  </body>
</html>

