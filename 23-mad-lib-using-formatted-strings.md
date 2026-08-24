###Mad Libs###
######This material is taken from the [LCHS Textbook](https://education.launchcode.org/lchs/chapters/strings/template-literals.html#check-your-understanding)

<p>Mad Libs are games where one player asks a group to supply random words
(e.g. “Give me a verb,” or, “I need a color”). The words are substituted
into blanks within a story, which is then read for everyone’s amusement.</p>

<p>Refactor the following code to replace the awkward string concatenation with
a template literal. Be sure to add your own choices for the variables!</p>

<p>Feel free to use either <code class="docutils literal notranslate"><span class="pre">.format()</span></code> or an f-string.</p>

```python.run
# Refactor the string concatenation to use either .format() or an f-string instead.
plural_noun = ''
name = ''
verb = ''
adjective = ''
color = ''

mad_lib = "Python provides a "+ color +" collection of tools — including " + adjective + " syntax and " + plural_noun + " — that allows "+ name +" to "+ verb +" with strings."

print(mad_lib)
```