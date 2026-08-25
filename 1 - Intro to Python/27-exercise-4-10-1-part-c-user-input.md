## Part C - User Input

#### Note

The ``len()`` function returns the number of characters in a string.

```python
  a_string = 'Rutabaga'

  print(len('the'))
  print(len(a_string))
```
**Console Output**
```
  3
  8
```

1. Prompt the user to enter a word, then use the ``len()`` function to find the number of characters in the word. Print the message, ``The word '___' contains __ characters.`` Fill in the blanks with the user's word and the number of characters. The output MUST include quotes around the word. For example:

    ```
    Enter a word: Tomato
    The word 'Tomato' contains 6 characters.
    ```

1. Prompt the user to enter the length and width for a rectangle. Calculate the area of the rectangle (length * width) and print the answer. The program should behave something like this:

    ```
    Rectangle length: 8
    Rectangle width: 4
    The rectangle has an area of 32.0.
    ```

1. Write a program that will find the *miles per gallon* for a car. Prompt the user to enter the number of miles driven and the number of gallons used. The program should behave something like this:

    ```
    How many miles did you drive? 280
    How many gallons did you use? 10
    Your car got 28.0 miles per gallon.
    ```
Note: You should be using the .format() method for printing strings!