<h1>4.1. Values and Data Types</h1>


<p>Programs are made up of two main things:</p>
<ol class="arabic simple">
<li>Data</li>
<li>Operations that do stuff with the data</li>
</ol>
<p id="index-0">Let’s start by looking at <strong>data</strong>, which is any piece of information stored in
a program. The most basic unit of data is called a <strong>value</strong>.</p>
<p>A <strong>value</strong> is a specific piece of data, such as a word or a number. Some
examples are <code class="docutils literal notranslate"><span class="pre">5</span></code>, <code class="docutils literal notranslate"><span class="pre">"Hello,</span> <span class="pre">World!"</span></code>, and <code class="docutils literal notranslate"><span class="pre">11.333</span></code>.</p>
<p id="index-1">Each value is an example of a <strong>data type</strong>. We will use many different data
types in this course, but here are your first three:</p>
<ol class="arabic simple">
<li><strong>string</strong> - One or more characters enclosed in quotes, such as
<code class="docutils literal notranslate"><span class="pre">"Hello,</span> <span class="pre">World"</span></code>. In Python, strings can be enclosed in single quotes or
double quotes, so <code class="docutils literal notranslate"><span class="pre">'A'</span></code> and <code class="docutils literal notranslate"><span class="pre">"B"</span></code> both count as strings.</li>
<li><strong>int</strong> - Stands for <strong>integer</strong>, which is a whole number like <code class="docutils literal notranslate"><span class="pre">4</span></code>, <code class="docutils literal notranslate"><span class="pre">-23</span></code>,
and <code class="docutils literal notranslate"><span class="pre">42</span></code>.</li>
<li><strong>float</strong> - Any number with a decimal like <code class="docutils literal notranslate"><span class="pre">3.14159</span></code>, <code class="docutils literal notranslate"><span class="pre">-0.01</span></code>, and <code class="docutils literal notranslate"><span class="pre">3.0</span></code></li></ol>

<p >
If you are not sure of the data type for a value, Python has the type() function to let us know!</p>

```python.run
print(type("Hello, World!"))
print(type(17))
print(type(3.14))
```
<hr>
<h2>4.1.1. More On Strings<a class="headerlink" href="#more-on-strings" title="Permalink to this headline">¶</a></h2>

<p class="first">What about values like <code class="docutils literal notranslate"><span class="pre">"17"</span></code> and <code class="docutils literal notranslate"><span class="pre">"3.2"</span></code>? They look like numbers, but
they are in quotation marks like strings.</p>
<p>Run the following code to find out.</p>

```python

print(type("17"))

print(type("3.2"))

```
<ol class="arabic" id="quote-reminder">
<li><p class="first">In Python we can use either single quotes (<code class="docutils literal notranslate"><span class="pre">'</span></code>) or double quotes (<code class="docutils literal notranslate"><span class="pre">"</span></code>) for
strings. <strong>Triple</strong> quotes (<code class="docutils literal notranslate"><span class="pre">'''</span></code> or <code class="docutils literal notranslate"><span class="pre">"""</span></code>) can be used for multi-line
strings.</p></li>
<li>Double-quoted strings can contain single quotes inside them, like <code>"Bruce's beard"</code>.</li>

<li>Single-quoted strings can have double quotes inside them, like <code>'The knights who say "Ni!"'</code>.</li>

<li>Python doesn’t care whether you use single or double quotes around strings, since the quote marks are not stored as part of the value.</li>

</ol>



