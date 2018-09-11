##PPOL 670-01 Fall 2018
### Problem Set 1* - Due by 11:59 on Monday, September 17

*Submission Instructions* Create a Python script called *pset1_netid.py* and a text file called *pset1_netid.txt*, except in both cases, replace "netid" with your Georgetown netid. All responses for Parts 1, 2, and 3 should be submitted on Canvas as part of the text file, and all code for Parts 2 and 3 should be submitted on Canvas as part of the Python script.

#### Part 1 - Data Types
Examine the following code:
```python
x = 5.3
print(x)
print(type(x))
int(x)
print(x)
print(type(x))
```

(a) Before executing any code, make a prediction of what the output will be.  Then run the code.  If your prediction was wrong, figure out why, and write a brief explanation.
(b) What is the type of the variable `x` after line 1 is run?
(c) What is the type of the variable `x` at the end of the script?
(d) Did the type of the variable `x` change at any point during the running of the code? If so, which line of code changed the type?  If not, why not?

#### Part 2 - Errors
For each of the following, explain why Python returns an exception.  Then, make a change to the code that would eliminate the error.  Include the revised code in your *pset1_netid.py* script.

```python
'Hello, world.
3 +
'abc' + 3
```

#### Part 3 - Conditionals, Loops, and Functions
Define a function called `exclaim()` that takes a string and returns `True` fi the string contains at least one exclamation point.  Otherwise it should return `False`.  You must use a `for` or `while` loop as part of your function definition.  If your function works correctly, `exclaim("p!ayer")` should return `True` and `exclaim("apple")` should return `False`. Include your function definition along with statements to evaluate it in your *pset1_netid.py* script.


*Adapted from CSCI-A 201/597 taught by Erik Wennstrom
