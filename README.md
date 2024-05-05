# BigThinkAI (UMD)  - *Data Science Lessons*

Created by: **Hevander Da Costa**

## Table of Contents

1. [Overview](#Overview)
2. [Contents](#Contents)
3. [Video Walkthrough](#Video-Walkthrough)
4. [Note](#Note)


## Overview
This repository contains the data science lession I designed for the the University of Maryland Club, BigThinkAI, as the data science lead.
The lessons represent an beginner to intermediate course in data science using Pandas,Matplotlib, Seaborn, and Numpy.


## Contents

The following **subjects** are covered:

- [X] Week1DS: Pandas , Data Manipulation , QQ-Plot Histogram Filtering and Indexing Grouping Pivot Tables  
- [X] Week2NB:  Data Cleaning  
- [X] WeeK4DS:  Analytics base tables, Data Quality Report, Imputation Data Transformation



## Video Walkthrough

https://github.com/Hevander27/BigThinkAi/assets/45948489/ecca6f01-88c9-4b7c-a089-15461ffe95e1


**Other Videos**

[BigThinkAI Lesson 1](https://www.youtube.com/watch?v=5gPmyA63o7k&t=1970s)
[BigThinkAI Lesson 2](https://www.youtube.com/watch?v=OPm83_gtqFI)
[BigThinkAI Lesson 3](https://www.youtube.com/watch?v=2A4NMiveKhI)


## Note
The repository contains duplicate files, DS refers to the instructors copy and NB refers to the student copy. 
The three notebooks above cover all the subjects described and show full implementation.


---
jupyter:
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
  language_info:
    codemirror_mode:
      name: ipython
      version: 3
    file_extension: .py
    mimetype: text/x-python
    name: python
    nbconvert_exporter: python
    pygments_lexer: ipython3
    version: 3.6.7
  nbformat: 4
  nbformat_minor: 2
---

<div class="cell markdown">

# Sample review module

</div>

<div class="cell markdown">

## Exercsie 1

Write code that adds two numbers together.

</div>

<div class="cell code">

``` python
def add_these_numbers(a,b):
    """Adds `a` and `b` and returns the
    sum as the `result` variable
    
    Arguments:
    `a`: An integer or a float
    `b`: An integer or a float
    
    Output:
    `result`: An integer or a float
    
    Example:
    If you call add_these_numbers(5,6),
    the output should be 11    
    """
    # YOUR CODE HERE
    
    raise NotImplementedError() # Remove this line when you enter your solution
    
    return result
```

</div>

<div class="cell markdown">

## Exercise 2

What is your favorite color?

-   A. Blue
-   B. Green
-   C. Purple
-   D. Yellow

</div>

<div class="cell code">

``` python
def ex_2():
    """
    Assign a letter to the variable `answer`,
    and then return it.
    """
    
    # YOUR CODE HERE
    raise NotImplementedError() # Remove this line when you enter your solution
    
    #answer = "A"
    #answer = "B"
    #answer = "C"
    #answer = "D"
    
    return answer
```

</div>

<div class="cell markdown">

## Testing Cells

Run the below cells to check your answers. Make sure you run your
solution cells first before running the cells below, otherwise you will
get a `NameError` when checking your answers.

</div>

<div class="cell code">

``` python
# Ex. 1
assert add_these_numbers(2,3) == 5, "Ex. 1 - Not quite, did you add the numbers or do something else? Check case 0.2 for a refresher!"
print("Exercise 1 seems correct!")
```

</div>

<div class="cell code">

``` python
# Ex. 2
assert ex_2() == "D", "Ex. 2 - You are flung into the abyss"
print("Right, off you go")
```

</div>







