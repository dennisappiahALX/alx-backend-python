# 0x00. Python - Variable Annotations

## Description

Variable annotations are a way to provide information about the expected type of a variable when you declare it in your code. They are written after the variable name, followed by a colon and the type of the variable. Variable annotations are not enforced by the Python interpreter, but they can be useful for static analysis tools like linters and type checkers. These tools can use the annotations to check that variables are being used correctly and to provide hints to developers.

+ At the end of this project, I was expected to be able to explain to anyone, without the help of Google:
   * Type annotations in Python 3
   * How you can use type annotations to specify function signatures and variable types
   * Duck typing
   * How to validate your code with mypy

---
## Tasks

+ [x] [0. Basic annotations - add](./0-add.py)

+ Write a type-annotated function add that takes a float a and a float b as arguments and returns their sum as a float.

+ [x] [1. Basic annotations - concat](./1-concat.py)

+ Write a type-annotated function concat that takes a string str1 and a string str2 as arguments and returns a concatenated string

+ [x] [2. Basic annotations - floor](./2-floor.py)

+ Write a type-annotated function floor which takes a float n as argument and returns the floor of the float.

+ [x] [3. Basic annotations - to string](./3-to_str.py)

+ Write a type-annotated function to_str that takes a float n as argument and returns the string representation of the float.

+ [x] [4. Define variables](./4-define_variables.py)

+ Define and annotate the following variables with the specified values:

+ [x] [5. Complex types - list of floats](./5-sum_list.py)

+ Write a type-annotated function sum_list which takes a list input_list of floats as argument and returns their sum as a float.

+ [x] [6. Complex types - mixed list](./6-sum_mixed_list.py)

+ Write a type-annotated function sum_mixed_list which takes a list mxd_lst of floats and integers and returns their sum as a float.

+ [x][7. Complex types - string and int/float to tuple](./7-to_kv.py)

+ Write a type-annotated function to_kv that takes a string k and an int OR float v as arguments and returns a tuple. The first element of the tuple is the string k. The second element is the square of the int/float v and should be annotated as a float.

+ [x] [8. Complex types - functions](./8-make_multiplier.py)

+ Write a type-annotated function make_multiplier that takes a float multiplier as argument and returns a function that multiplies a float by multiplier.

+ [x] [9. Let's duck type an iterable object](./9-element_length.py)

+ Annotate the below function’s parameters and return values with the appropriate types

+ [x] [10. Duck typing - first element of a sequence](./100-safe_first_element.py)

+ Augment the following code with the correct duck-typed annotations:
+ [x] [11. More involved type annotations](./101-safely_get_value.py)

+ Given the parameters and the return values, add type annotations to the function

+ [x] [12. Type Checking](./102-type_checking.py)

+ Use mypy to validate the following piece of code and apply any necessary changes.

---
