
<h2>4.4.1. Naming Python Variables<a class="headerlink" href="#naming-python-variables" title="Permalink to this headline">¶</a></h2>
<p>Just like the <code class="docutils literal notranslate"><span class="pre">print</span></code> function must follow specific syntax rules, variable
names in Python have their own set of rules:</p>
<ol class="arabic simple">
<li>Variable names MUST begin with a letter or an underscore <code class="docutils literal notranslate"><span class="pre">_</span></code>.</li>
<li>Variable names CANNOT contain spaces. If you have more than one word in a
name, connect the words with underscores (e.g. <code class="docutils literal notranslate"><span class="pre">price_of_eggs</span></code>).</li>
<li>Variable names may only use letters (a-z and A-Z), underscores (_), and
numbers (0-9).</li>
<li>Case matters! <code class="docutils literal notranslate"><span class="pre">animal</span></code> and <code class="docutils literal notranslate"><span class="pre">Animal</span></code> are different variable names.</li>
</ol>
<p>In addition to these rules, there are also some *conventions*. These are
habits that Python programmers follow to keep their code consistent with
others’ across the world. You do not have to follow these suggestions, but you
really <strong>SHOULD</strong>:</p>
<ol class="arabic simple">
<li>Use names that clearly describe their values. For example, if you need to
store the price of eggs, call your variable <code class="docutils literal notranslate"><span class="pre">price_of_eggs</span></code> instead of
<code class="docutils literal notranslate"><span class="pre">x</span></code>. Similarly, <code class="docutils literal notranslate"><span class="pre">vowel</span></code> makes more sense than <code class="docutils literal notranslate"><span class="pre">v</span></code>.</li>
<li>Stick to lowercase letters and underscores in the variable name, unless the
value is a constant.</li>
<li>Use all UPPERCASE to name constants (e.g. <code class="docutils literal notranslate"><span class="pre">PI</span></code> or <code class="docutils literal notranslate"><span class="pre">SPEED_OF_LIGHT</span></code>).</li>
</ol>

<h3>4.4.1.1. Compare<a class="headerlink" href="#compare" title="Permalink to this headline">¶</a></h3>
<p>Writing good code is about more than just solving the task at hand. It also
includes making the code easy to read, update, and maintain.</p>
<p>Consider these examples of variable names:</p>

```
x = 5
y = 3.14
z = y * x ** 2
print(z)
```
<p>What is this program doing? Hard to say. The variable names <code class="docutils literal notranslate"><span class="pre">x</span></code>, <code class="docutils literal notranslate"><span class="pre">y</span></code>,
and <code class="docutils literal notranslate"><span class="pre">z</span></code> don’t tell us anything about how they are used.</p>
<p>Let’s look at an improved version of this program.</p>
<p><strong>Stronger variable names</strong>:</p>

```
radius_of_circle = 5
PI = 3.14
area_of_circle = PI *radius_of_circle ** 2
print(area_of_circle)
```

<p class="last">With improved variable names, it becomes clear that the program is
calculating the area of a circle of radius 5. Here’s another benefit of descriptive variable names.
Although we have not yet learned what the symbols <code>\*</code> and <code class="docutils literal notranslate"><span class="pre">\*\*</span></code> do on line 3, the variable
names give us an idea of what the symbols mean.</p>

Some special words (*keywords* in Python) cannot be used as variable names. 
For example, you cannot assign a variable called <code>print</code>

You can read more about keywords here: [4.4.2 Keywords](https://education.launchcode.org/lchs/chapters/data-and-variables/more-on-variables.html#keywords)

Now, complete the [4.4.4 Check Your Understanding](https://education.launchcode.org/lchs/chapters/data-and-variables/more-on-variables.html#check-your-understanding)
