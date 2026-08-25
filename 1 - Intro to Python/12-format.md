##.format()##

<p>Suppose you want to display the following sentence:</p>
<strong>My name is Bert and this is my good friend Ernie.</strong>  
<br

<p>You could do that using the following code:</p>


```
name = "Bert"
friend = "Ernie"
print("My name is",name, "and this is my good friend", friend+".")

```
<p>This is kind of a *pain*. You need to remember where to put commas, where to put your variable(s), and you even have to use a <code>+</code> so that you *don't* get a space between **'Ernie'** and **'.'**.

<p>Worst yet, your sentence is still gramatically incorrect! (Shouldn't it have a comma between **'Bert'** and **'and'**?</p>

<p>Python has a feature to make using variables inside of strings a bit easier. We are going to practice this a ton, and you can read up on it [in the textbook here](https://education.launchcode.org/lchs/chapters/strings/template-literals.html?highlight=format#the-format-method)</p>

```python.run
wait = input("Press Enter")
name = "Bert"
friend = "Ernie"
print("My name is {}, and this is my good friend {}.")
```
<p>Let's edit the code to add <code>.format()</code> after the string</p>
<p>Inside the parentheses, we are going to add our two variables. Think of this a filling in the blanks in the 'squiggly brackets' </p>
<p>That would look like this: <code>.format(name, friend)</code></p>


<p>This is called a *template literal*, and it allows for the automatic insertion of expressions and variable values into strings</p>