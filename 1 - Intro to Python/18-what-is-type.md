<p>So far we have learned about three data types:</p>
<ul>
<li>int - used for numbers without decimal places</li>
<li>float - used for numbers with decimal places</li>
<li>string - used for text or multiple characters</li>
</ul>

<p>Python will automatically recognize the difference between a int and a float. If you need to know what type something is, you can use the print(type()) sequence.</p>

```python.run
num_1 = 12
num_2 = 14.4

print(type(num_1))
print(type(num_2))
```

<p>Unfortunately, a string and a number won't necessarily look different <i>to you</i>.</p>

```python.run
num_1 = 17.07
string_1 = "17.07"

print(num_1)
print(string_1)

print("\n")

print(type(num_1))
print(type(string_1))
```

<p>In this case, you would need to use print(type()) if you weren't sure which type your data was in. The reason this matters is because python interacts with different types differently.</p>
<h4>Example of why type matters</h4>
```python.run
print(2000*3)
print("2000"*3)
```

<p>The following will randomly select one of the items to print. How can you know which one printed?</p>
```python.run
import random
object_list = [1985, 1992, "1985","boat",42.5,"42.5",1992.0,1985.0]

item = random.choice(object_list)
print(item)
```