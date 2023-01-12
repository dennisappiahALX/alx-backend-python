# 0x02. Python - Async Comprehension

## Description

+ In this project I practised Learning Async Comprehension while  doing the tasks in python.

## Prerequisites/Requirements

---
* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/env python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the pycodestyle style (version 2.5.x)
* The length of your files will be tested using wc
* All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All your functions should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)'
* All your functions and coroutines must be type-annotated.

---

## Tasks

+ [x] [0. Async Generator](./0-async_generator.py)

 + Write a coroutine called async_generator that takes no arguments.

+ [x] [1. Async Comprehensions](./1-async_comprehension.py)

 + Import async_generator from the previous task and then write a coroutine called async_comprehension that takes no arguments.

+ [x] [2. Run time for four parallel comprehensions](./2-measure_runtime.py)

 + Import async_comprehension from the previous file and write a measure_runtime coroutine that will execute async_comprehension four times in parallel using asyncio.gather.

---
