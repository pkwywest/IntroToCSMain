##print(f"##

<p>An alternative to <code>.format</code> is to use the <code>print(f"</code></p>

<strong>My name is Bert and this is my good friend Ernie.</strong>  


<p>You could do that using the following code:</p>


```
name = "Bert"
friend = "Ernie"
print("My name is",name, "and this is my good friend", friend+".")

```
####or####
```
name = "Bert"
friend = "Ernie"
print("My name is {}, and this is my good friend{}".format(name, friend))

```

<p>This definitely solves the problem of _writing_ the code. Once you get the hang of it, <code>.format()</code> is very easy to use.</p>

<p>However, you could improve upon the readability of your code. If you asked an "average person" to look at your code, the <code>.format()</code> might slow them down or confuse them. </p>

<p>A _newer_ feature is the <code>print(f" </code> string formatting mechanism. Since this name is a little off-putting, most sites will refer to these as <strong>"f strings"</strong>. You can find this [in the textbook here](https://education.launchcode.org/lchs/chapters/strings/template-literals.html#f-strings).</p>

<p>The part that takes the most getting used to is the order of the keyword and syntax</p>

<strong>print(</strong> <strong>f"</strong> String to be formatted <strong>")</strong>

```python.run
wait = input("Press Enter")
name = "Bert"
friend = "Ernie"
print(f"My name is {}, and this is my good friend {}.")
```
<p>Let's edit the code to add variables in the curly braces in the string</p>
<p>Inside the braces, we are going to add our two variables. Think of this a filling in the blanks in the 'squiggly brackets' </p>



<p>This is called a *template literal*, and it allows for the automatic insertion of expressions and variable values into strings</p>