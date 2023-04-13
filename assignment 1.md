Q1. Write all the conventions being followed while declaring a variable.
Ans:-A variable name must start with a letter or an underscore character (_) A variable name cannot start with a digit. A variable name can only contain alpha-numeric characters and underscores ( a-z, A-Z , 0-9 , and _ ) Variable names are case-sensitive (age, Age and AGE are three different variables)

Q2. What will happen if we declare a restricted keyword as a variable?
Ans:-The Python programming language, if you try to declare a variable with a restricted keyword such as "if" or "while", you will get a syntax error .
    It is always a good practice to avoid using restricted keywords as variable names and to follow the naming conventions of the programming language you are using to ensure that your code is syntactically correct and easy to read.

Q3. Can we actually declare a string as a variable name?
Ans:-In most programming languages, it is not possible to declare a string literal as a variable name. Variable names in programming languages usually consist of a combination of letters, digits, and underscores, and they typically cannot begin with a digit. However, some languages like Python do allow strings as variable names, but it is not a common practice to do so as it can make the code harder to read and understand.



Q4. Is it possible for us to declare “_” as a variable? If so, then write an example of it.
Ans:-Yes, in most programming languages, it is possible to declare a variable with the name "_". In fact, in some programing languages, such as Python, the underscores character is commonly used as a throwaway variable name or to indicate that a variable is not needed.
example
_ = 2569
print(_)
output:-2569


Q5. Using an example, explain how the variables in python are dynamic in nature.
Ans:-
In Python, variables are dynamic in nature, which means that they can change their type and value at runtime. This makes Python a dynamically typed language. 
example:-
#declare a variable and assign an integer value to it
x = 5

#print the value of x and its type
print(x)
print(type(x))

#assign a string value to the same variable x
x = "hello world"

#print the value of x and its type
print(x)
print(type(x)
Output:-
5
<class 'int'>
hello world
<class 'str'>


```python

```
