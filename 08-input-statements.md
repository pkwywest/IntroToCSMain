
<h1>4.9. User Input<a class="headerlink" href="#user-input" title="Permalink to this headline">¶</a></h1>
<p><code class="docutils literal notranslate"><span class="pre">print</span></code> works fine to display messages on the screen that never change. If we
want to display different messages, we could try adding a variable:</p>
<h4>Example:</h4>
<p>Run the code below, then change the value of <code class="docutils literal notranslate"><span class="pre">name</span></code> to make the program
greet you by name!</p>  

```python.run
# Run the code as-is first, then try changing the value of 'name.'
name = 'Rutabaga'
print("Hello, " + name + "!")

# Next, read about the input() function below.
```
<p>To print a greeting for a specific user, <code class="docutils literal notranslate"><span class="pre">print("Hello</span> <span class="pre">Dave!")</span></code> only works if
Dave is the actual user. To greet someone else, we could change the string
inside the <code class="docutils literal notranslate"><span class="pre">()</span></code> to be <code class="docutils literal notranslate"><span class="pre">'Hello</span> <span class="pre">Sarah!'</span></code> or <code class="docutils literal notranslate"><span class="pre">'Hello</span> <span class="pre">Elastigirl!'</span></code> or any
other name we need.</p>
<p>Similarly, to make the statement <code class="docutils literal notranslate"><span class="pre">print("Hello,</span> <span class="pre">"</span> <span class="pre">+</span> <span class="pre">name</span> <span class="pre">+</span> <span class="pre">"!")</span></code> work for
different users, we need to go into the code and change the string we assign to
<code class="docutils literal notranslate"><span class="pre">name</span></code>.</p>
<p>However, what if we do not know the name of the user beforehand?</p>
<p>It would be great if we could ask the user of our program to enter a name, save that string,
and then print a personalized greeting.</p>
<p>Of course, Python gives us a way to do this!</p>


<h2>4.9.1. Requesting Data<a class="headerlink" href="#requesting-data" title="Permalink to this headline">¶</a></h2>
<p id="index-0">To personalize the greeting, we need <strong>input</strong> from the user. This
involves displaying a <strong>prompt</strong> on the screen (e.g. <code class="docutils literal notranslate"><span class="pre">Please</span> <span class="pre">enter</span> <span class="pre">a</span> <span class="pre">number:</span></code>), and then
saving the response from the user. Whatever information the user
enters can be stored in a variable.</p>
<p>Python has a built-in function to collect information from a user. As you might
expect, it is called <code class="docutils literal notranslate"><span class="pre">input</span></code>.</p>

<h3>4.9.1.1. Syntax<a class="headerlink" href="#syntax" title="Permalink to this headline">¶</a></h3>
<pre><span></span><span class="n">variable_name</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s1">'User prompt...'</span><span class="p">)</span>
</pre>
<p>The keyword <code class="docutils literal notranslate"><span class="pre">input</span></code> tells Python to display the prompt in the console. It
then waits for the user to type in some information. Once the user taps <strong>Enter</strong>
or <strong>Return</strong>, the data is collected and stored in the variable.</p>

<h4>Note:</h4>
<p>There is a lot going on here behind the scenes, but for now you should
follow this bit of wisdom:</p>
<blockquote>
I turn the key, and it goes.</blockquote>
<p class="last">Most of us do not need to know exactly how cars, phones, or microwave ovens
work. We just know enough to use them in our day to day lives. Similarly, we
do not need to understand <strong>how</strong> <code class="docutils literal notranslate"><span class="pre">input()</span></code> collects data from the console. We
just need to know that it <strong>does</strong> if we use the correct syntax.</p>

<h3>4.9.1.2. Try It!<a class="headerlink" href="#try-it" title="Permalink to this headline">¶</a></h3>
<p>In the editor above:</p>
<ol class="arabic simple">
<li>Replace line 2 with <code class="docutils literal notranslate"><span class="pre">name</span> <span class="pre">=</span> <span class="pre">input('Please</span> <span class="pre">enter</span> <span class="pre">your</span> <span class="pre">name:</span> <span class="pre">')</span></code>.</li>
<li>Run the program again. You should see the text <code class="docutils literal notranslate"><span class="pre">Please</span> <span class="pre">enter</span> <span class="pre">your</span> <span class="pre">name:</span></code>
appear in the righthand box (the <strong>console </strong>).</li>
<li>In the console, type in a name, tap <strong>Enter</strong>, and examine the result.</li>
<li>Run the program several more times and enter different names.</li>
</ol>
<p>Try adding another <code class="docutils literal notranslate"><span class="pre">+</span> <span class="pre">name</span></code> term inside the <code class="docutils literal notranslate"><span class="pre">print</span></code> statement and see
what happens. Next, add code to prompt the user for a second name. Store the
response in <code class="docutils literal notranslate"><span class="pre">other_name</span></code>, then print both names using <code class="docutils literal notranslate"><span class="pre">print</span></code>.</p>

<h2>4.9.2. Using the Collected Data<a class="headerlink" href="#using-the-collected-data" title="Permalink to this headline">¶</a></h2>
<p>After collecting a name, the program does not actually DO anything with the
information. If we want to use the data, we need to tell Python what to do with
the <code class="docutils literal notranslate"><span class="pre">name</span></code> variable.</p>
<p>By storing the user’s name inside the variable called <code class="docutils literal notranslate"><span class="pre">name</span></code>, we gain the ability to hold onto
the data and use it when we want.</p>
<h4>Try It:</h4>
<p>Write a program that requests a user’s first and last name, then prints an
output that looks like:</p>
<pre><span></span>First name: Elite
Last name: Coder
Last, First: Coder, Elite
</pre>

```python.run
# Use input statements to collect the user's first and last names.
first_name = ''
last_name = ''

# Code your print statements here:

# Bonus: Since we know how to use the .format() method, 
# you shouldn't need to use '+' to concatenate strings basically *ever* again.
```
<h2>4.9.3. Critical <code class="docutils literal notranslate"><span class="pre">input</span></code> Detail<a class="headerlink" href="#critical-input-detail" title="Permalink to this headline">¶</a></h2>
<p>There is one <strong>very important</strong> quirk about the <code class="docutils literal notranslate"><span class="pre">input</span></code> function that we need to
remember. </p>
<p>Given <code>print(7 + 2)</code>, the output would be <code>9</code>.</p>
<p>Now explore the following code, which prompts the user for two numbers and then prints their sum:</p>  

```python.run
num_1 = input("Enter a number: ")
num_2 = input("Enter another number: ")

print(num_1 + num_2)
```
<p>Do you see the output you expected?</p>
<p>If we enter <code class="docutils literal notranslate"><span class="pre">7</span></code> and <code class="docutils literal notranslate"><span class="pre">2</span></code>, we may expect an output of <code class="docutils literal notranslate"><span class="pre">9</span></code>. The result printed is <code class="docutils literal notranslate"><span class="pre">72</span></code>. What gives?!?!?</p>
<p id="index-1">The quirk with the <code class="docutils literal notranslate"><span class="pre">input</span></code> function is that it <i>treats all entries as
strings</i>, so numbers get <strong>concatenated</strong> rather than added. Concatenation
means that the second string gets attached to the end of the first.</p>
<p>Just like <code class="docutils literal notranslate"><span class="pre">"ABC"</span> <span class="pre">+</span> <span class="pre">"def"</span></code> outputs as <code class="docutils literal notranslate"><span class="pre">ABCdef</span></code>, <code class="docutils literal notranslate"><span class="pre">"7"</span></code> + <code class="docutils literal notranslate"><span class="pre">"2"</span></code> outputs
as the string <code class="docutils literal notranslate"><span class="pre">72</span></code>.</p>
<blockquote>
Python treats input data as strings!</blockquote>
<p>If we want our program to perform math operations on the entered numbers, we must
[use type conversion ](https://education.launchcode.org/lchs/chapters/data-and-variables/type-conversion.html) to change the string values into
numbers.</p>

<h4>Try It:</h4>
<ol class="last arabic">
<li><p class="first">In the print statement, use <code class="docutils literal notranslate"><span class="pre">int()</span></code> to convert <code class="docutils literal notranslate"><span class="pre">num_1</span></code> and <code class="docutils literal notranslate"><span class="pre">num_2</span></code>
from strings to integers. Run the program and examine the result.</p>
</li>
<li><p class="first">Instead of collecting <code class="docutils literal notranslate"><span class="pre">num_1</span></code> as a string and then converting it later,
we can do this in a single step. In line 1, place
<code class="docutils literal notranslate"><span class="pre">input("Enter</span> <span class="pre">a</span> <span class="pre">number:</span> <span class="pre">")</span></code> inside the <code class="docutils literal notranslate"><span class="pre">int()</span></code> function like this:</p>
<p><code class="docutils literal notranslate"><span class="pre">int(input("Enter</span> <span class="pre">a</span> <span class="pre">number:</span> <span class="pre">"))</span></code>.</p>
</li>
<li><p class="first">Repeat step 2 for <code class="docutils literal notranslate"><span class="pre">num_2</span></code>.</p>
</li>
<li><p class="first">Remove the <code class="docutils literal notranslate"><span class="pre">int</span></code> functions from the print statement. Run the program
and examine the result.</p>
</li>
<li><p class="first">What happens if you enter <code class="docutils literal notranslate"><span class="pre">Hi</span></code> or <code class="docutils literal notranslate"><span class="pre">4.33</span></code> instead of a whole number?</p>
</li>
</ol>
[Now go to the textbook to Check Your Understanding](https://education.launchcode.org/lchs/chapters/data-and-variables/input.html#check-your-understanding)