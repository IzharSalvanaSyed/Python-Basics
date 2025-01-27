# Python-Basics
Exploring the basic concepts of Python. Discover how to use Python both interactively and through scripting. Create your first variables and familiarize yourself with Python's basic data types.

## Table of contents

1. [Intro](#hello)
2. [First Python Code](#first)
3. [Python Calculator](#caluclator)
4. [Variables and Types](#vartypes)
5. [Variable Assignments](#varassign)
6. [Calculations With Variables](#calcvar)
7. [Other Variable Types](#vartypes)
8. [Operations With Other Types](#othertypes)
9. [Other Types](#types)

## Hello <a name="hello">
I will start to learn Python for Data science. Python can be used for general purposes to build anything. It is open source and can have many packages to help you with your needs.  

- Write more about python here  

## First Python Code <a name="first">
Using your (Code) and type  
1`# Example, do not modify!`  
2`print(5 / 8)`  
3  
4`# Print the sum of 7 and 10`  
5`print(7+10)`  

Run the code and see the output  

`# Example, do not modify!
print(5 / 8)`

`# Print the sum of 7 and 10
print(7+10)
0.625
17`

## Python Calculator <a name="calculator">
Using your (Code) and type  
1`# Addition`  
2`print(4+5)`  
3  
4`# Subtraction`  
5`print(5-5)`  
6  
7`# Multiplication`  
8`print(3*5)`  
9  
10`# Division`  
11`print(10/2)`  

Run the code and see the output  

1 `# Addition`  
2 `print(4+5)`  
3  
4 `# Subtraction`  
5 `print(5-5)`  
6  
7 `# Multiplication`  
8 `print(3*5)`  
9  
10 `# Division`  
11 `print(10/2)`  
12 `9`  
13 `0`  
15  
16 `5.0`  

## Variables and Types <a name="vartypes">
A Python variable is a reserved memory location to store values. In other words, a variable in a python program gives data to the computer for processing. Every value in Python has a datatype. Different data types in Python are Numbers, List, Tuple, Strings, Dictionary, etc..

### Variables
- Specific, case-sensitive name
- Call up value through a variable name

### Calculate BMI with Variables
if we put Varibles `height` and have it equal  `1.79` and another variable `weight` and have that equal `68.7`. If we recall `height` it will give us back the value of `1.79`.  

To calculate BMI we need to use the Equation `BMI = Weight / height^2`.  
`68.7 / 1.79**2  |  weight / height**2`  
`   21.4413      |     21.4413`

Now we can just create a Variable called `bmi`.  
`bmi = weight / height**2`  
When we recall this variable `bmi` it will take our `height` and `weight` variables already give us the answer of the BMI equaition we created as a Varible taking in our other Variables we created
`bmi`  
`21.4413`  

## Operations With Other Types <a name="othertypes">
Variables come in different types in Python. You can see the type of a variable by using type(). For example, to see type of a, execute: type(a).  
Different types behave differently in Python. When you sum two strings, for example, you'll get different behavior than when you sum two integers or two booleans.  
Time for you to test this out.In Python, variables come in different types. You can check the type of a variable by using the `type()` function. For example, to see the type of a variable named `a`, you would execute: `type(a)`.  

Different types behave differently in Python. For instance, when you add two strings together, the behavior will differ from adding two integers or two booleans.  

**Instructions 1**  
Add savings and new_savings and assign it to total_savings.  
Use type() to print the resulting type of total_savings.  

1 `savings = 100`  
2 `new_savings = 40`  
3  
4 `# Calculate total_savings using savings and new_savings`  
5 `____`  
6 `print(total_savings)`  
7  
8  `# Print the type of total_savings`  
9  `print(____)`  

Answer  
1 `savings = 100`  
2 `new_savings = 40`  
3  
4 `# Calculate total_savings using savings and new_savings`  
5 `total_savings = savings + new_savings`  
6 `print(total_savings)`  
7  
8  `# Print the type of total_savings`
9  `print(type(total_savings))`  

**Instructions 2**  
Calculate the sum of intro and intro and assign the result to doubleintro. 
Print out doubleintro.  

Sample  
1 `intro = "Hello! How are you?"`   
2   
3 `# Assign sum of intro and intro to doubleintro`   
4 `____`   
5  
6 `# Print out doubleintro`    
7 `print(____)`    

Answer  
1 `intro = "Hello! How are you?"`   
2   
3 `# Assign sum of intro and intro to doubleintro`   
4 `doubleintro = intro + intro`   
5  
6 `# Print out doubleintro`    
7 `print(doubleintro)`    

output  
`intro = "Hello! How are you?"`  
  
`# Assign sum of intro and intro to doubleintro`  
`doubleintro = intro + intro`  
  
`# Print out doubleintro`  
`print(doubleintro)`  
`Hello! How are you?Hello! How are you?`  

## Other Types <a name="types">
In Python, variables come in different types. You can check the type of a variable by using the `type()` function. For example, to see the type of a variable named `a`, you would execute: `type(a)`.  

Different types behave differently in Python. For instance, when you add two strings together, the behavior will differ from adding two integers or two booleans.  

instructions:

- Create a new float, half, with the value 0.5.  
- Create a new string, intro, with the value "Hello! How are you?".  
- Create a new boolean, is_good, with the value True.  

**Script**  
1 `# Create a variable half `    
2 `half = 0.5  `    
3  
4 `# Create a variable intro `    
5 `intro = "Hello! How are you?"`     
6     
7 `# Create a variable is_good `    
8 `is_good = True  `   

**output**  
`# Create a variable half`  
`half = 0.5`  
  
`# Create a variable intro`  
`intro = "Hello! How are you?"`  
  
`# Create a variable is_good`  
`is_good = True`  
