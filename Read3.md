# what is a file?

a file is a contiguous set of bytes used to store data,This data is organized in a specific format and can be anything as simple as a text file or as complicated as a program executable. In the end, these byte files are then translated into binary 1 and 0 for easier processing by the computer.

## Files on most modern file systems are composed of three main parts:
1.Header

2.Data

3.End of file (EOF)

## The file path is a string that represents the location of a file. It’s broken up into three major parts:
1.Folder Path : where's location for this file

2.File Name: actual the name of the file 

3.Extension


## Opening and Closing a File in Python
when you want to open file in python This is done by invoking the open() built-in function

---

## Exceptions versus Syntax Errors
Syntax errors occur when the parser detects an incorrect statement

exception error: This type of error occurs whenever syntactically correct Python code results in an error.

---

## *What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?*

In Python, the with statement replaces a (try-catch) block with a concise shorthand. More importantly, it ensures closing resources right after processing them.

---

## ***Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.***

The read() will read the whole file at once and then print out the first characters that take up as many bytes as you specify in the parenthesis versus the readline() that will read and print out only the first characters that take up as many bytes as you specify in the parenthesis. 

---

## Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code?

The try...except block is used to handle exceptions in Python,
When an exception occurs, it is caught by the except block. The except block cannot be used without the try block.


