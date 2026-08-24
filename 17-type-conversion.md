<span id="id1"></span><h1>4.2. Type Conversion<a class="headerlink" href="#type-conversion" title="Permalink to this headline">¶</a></h1>
<span class="target" id="index-0"></span><p id="index-1">Sometimes it is necessary to convert values from one type to another. A common
example occurs when a program receives string input, like <code class="docutils literal notranslate"><span class="pre">"23"</span></code>, but needs
to use the value as a number.</p>
<p>Python provides a few simple <strong>type conversion</strong> functions that allow us to
change between data types. The functions <code class="docutils literal notranslate"><span class="pre">int()</span></code>, <code class="docutils literal notranslate"><span class="pre">float()</span></code> and <code class="docutils literal notranslate"><span class="pre">str()</span></code>
will try to convert whatever is in the <code class="docutils literal notranslate"><span class="pre">()</span></code> (the <strong>argument</strong>) into the types
<code class="docutils literal notranslate"><span class="pre">int</span></code>, <code class="docutils literal notranslate"><span class="pre">float</span></code> and <code class="docutils literal notranslate"><span class="pre">string</span></code>, respectively.</p>
<p>The <code class="docutils literal notranslate"><span class="pre">int()</span></code> function takes a floating point number or a string and turns it
into whole number. Instead of <strong>rounding</strong> a decimal value, <code class="docutils literal notranslate"><span class="pre">int()</span></code> <strong>discards</strong>
the decimal portion of the number.</p>
<h3>Example</h3>
<p>Let’s see <code class="docutils literal notranslate"><span class="pre">int()</span></code> in action. Run the following code and note how <code class="docutils literal notranslate"><span class="pre">int()</span></code>
changes the decimal values.</p>

```python.run
input("Press 'Enter'")
#Ignore the line above!
print(3.14, int(3.14))
print(3.9999, int(3.9999))   # This doesn't round to the closest int!
print(3.0, int(3.0))
print(-3.999, int(-3.999))   # 'Truncating' is not 'rounding'.

print("2345", int("2345"))   # Convert a string to an int
```
<p>What happens if we try to convert a string to an integer, but the string is not
actually a whole number? Add the following code to the editor above, then run
the program again. You should see an error message.</p>
```
print(int("80days"))
print(int("12.34"))
```
<p>In order for <code class="docutils literal notranslate"><span class="pre">int()</span></code> to work, the string has to be a whole number like
<code class="docutils literal notranslate"><span class="pre">'-2'</span></code> or <code class="docutils literal notranslate"><span class="pre">"526"</span></code>. Any string with letters, spaces, or punctuation will
throw an error. Modify the new examples by deleting the <code class="docutils literal notranslate"><span class="pre">days</span></code> and <code class="docutils literal notranslate"><span class="pre">.</span></code>,
then rerun the program. You should see the integers <code class="docutils literal notranslate"><span class="pre">80</span></code> and <code class="docutils literal notranslate"><span class="pre">1234</span></code>.</p>
<p>The type converter <code class="docutils literal notranslate"><span class="pre">float()</span></code> turns an integer or an allowed string into a
<code class="docutils literal notranslate"><span class="pre">float</span></code>. The type converter <code class="docutils literal notranslate"><span class="pre">str()</span></code> turns its argument into a <code class="docutils literal notranslate"><span class="pre">string</span></code>.</p>
<p>Remember that when we print a string, the quotes are removed. However, if we
use the <code class="docutils literal notranslate"><span class="pre">type()</span></code> function, we can see the data type.</p>

<p>Let’s see <code class="docutils literal notranslate"><span class="pre">float()</span></code> and <code class="docutils literal notranslate"><span class="pre">str()</span></code> in action.</p>
```python.run
input("Press 'Enter'")
#Ignore the line above!
print(4, float(4))

print("9.87", float("9.87"))
print(type("9.87"), type(float("9.87")))

print(str(42))
print(str(9.87), type(str(9.87)))
```

Now follow [this link](https://education.launchcode.org/lchs/chapters/data-and-variables/type-conversion.html#check-your-understanding) to check your understanding. 