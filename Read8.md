## **List Comprehensions**

***List comprehensions are a concise and efficient way to create new lists in Python. They allow you to define a new list based on an existing list or other iterable object, using a compact syntax that includes a loop and an optional conditional expression.***

**The basic syntax for a list comprehension is:**

**[expression for variable in iterable if condition]**

**Here, variable represents the current item being processed from the iterable, condition is an optional filter that allows you to include only certain items that meet a specific condition, and expression is the value that is generated for each item in the new list.**

## example:

[ expression for item in list ]

digits = [x for x in range(10)]

print(digits)

output>>[0,1,2,3,4,5,6,7,8,9]

**List comprehensions can be nested, and can also incorporate other Python features such as functions, tuples, and dictionaries.**

**Overall, list comprehensions provide a convenient and readable way to generate new lists that meet specific criteria, making them a popular tool among Python developers.**


## Decorators in Python are a language feature that allows you to modify or enhance the behavior of a function or a class without changing its source code. Essentially, a decorator is a higher-order function that takes in a function as an argument and returns a new function with added functionality.

## To use a decorator, you simply define a new function that uses the decorator syntax **@decorator_name** above the function definition. When the decorated function is called, the decorator function is executed first, and the returned function is then executed in its place.