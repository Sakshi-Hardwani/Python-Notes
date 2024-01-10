# Learning Python!

## Source
[Video link](https://youtu.be/_uQrJ0TkZlc?feature=shared)

## Outcomes
* Python from scratch
* Practise
* How to implement Python for AI/ML/Web Development
* Projects

---

## Installation
* Python
* PyCharm

---

## First Program

```
 print("HelloWorld")
```

```
print("Sakshi Hardwani")
print("o----")
print(" ||||")
print("*"*10)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/c81705b5-5e5b-4c36-88bf-f7d27eca54ae)

---

## Execution of Code

In Python execution of code is line by line.

---

## Variables
* integer
* flaot 
* string
* boolean
* complex values(list/objects)

```
price=10
price=20
rating=4.9
name='Sakshi'
is_published=False
print(price)
print(rating)
print(name)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/0dc5d6e3-3662-400c-9e96-6dd0af90814c)

---

## Receiving inputs

* input() is used to take input.
* Contactination is used to print two or more inputs.
 
---

## Type Conversion

With context to this example python can't perfrom operation like int-str i.e integer minus string so we need to convert the str to int. In below example birth year was taken as str before 2023-'2003' but after conversion int(birth_year) it is now understood as 2023-2003.

```
birth_year = input('Birth year: ')
print(type(birth_year))
age = 2023 - int(birth_year)
print(type(age))
print(age)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/1535fc96-9b98-42b7-b8bc-46f019f4820d)

Example
Ask user their weight (in pounds), convert it to kg and print on terminal.

```
weight_lbs = float(input('What is your weight?(lbs): '))
weight_kg = weight_lbs * 0.45
print(weight_kg)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/aaf199fa-e313-4c04-b9a3-b2d4824c5e77)

> Note: type is an inbuilt function (input and print are also)

---

## Strings

```
#use of quotes for string

course = 'Python course for Beginners'
print(course)

course = "Python's course for Beginners" #to write Python's
print(course)

course = 'Python course for "Beginners"'
print(course)

#use of ''' to write string of multiple lenghts

course='''
Hi Sakshi,
Here is our first email to you.

Thank You,
The support team
'''
print(course)

#To get index of first charcater

course = 'Python course for Beginners'
        # 012345 so at 0 index there is P
print(course[0])

course = 'Python course for Beginners'
print(course[-1])#negative index

course = 'Python course for Beginners'
print(course[0:3])#charcater of index from 0 to 2 will be printed

course = 'Python course for Beginners'
print(course[0:])

course = 'Python course for Beginners'
print(course[1:])

course = 'Python course for Beginners'
print(course[:5])

course = 'Python course for Beginners'
another = course[:]# course[:] copy/clone string as 0 is initial index and later lenght of string is assumed
print(another)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/9ba06f33-0fe6-4496-80c5-3a16c3e4752e)

---

## Formatted String

* Use to dynamically generate text with variables.
* With such contactinations it gets hard to visualise outputs.Therefore,we use this concept of formatted strings.
* To define formatted string prefix your string with f and use curly braces to dynamically insert values into string.

```
#To print such msg Sakshi [Hardwani] is a coder
first = 'Sakshi'
last = 'Hardwani'
#message = first + ' [' + last + '] is a coder ' #contactination method
msg = f'{first} [{last}] is a coder'#formatted string
print(msg)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/10c983d2-0719-45db-bacc-26407399aa55)

---

## String Methods

* len() for lenght of string .
* dot operator to access the functions or methods.
* upper()
* lower()
* title()
* find() to return index.
* replace() to replace.
* in operator to check string present or not , returned is a boolean value.

```
course = 'Python for Beginners'
#length of string
print(len(course))

#upper and lower case
print(course.upper())
print(course.lower())

#to return index
print(course.find('P')) 

print(course.find('O')) 
#-1 is return index as there is no capital O i.e. it is case sensitive

print(course.find('Beginners')) 
#11 is return index as Beginners start from B

#to replace
print(course.replace('Beginners', 'Absolute Beginners')) 
print(course.replace('P', 'J'))

# to check string present or not , returned is a boolean value
print('Python' in course)
print('python' in course)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/80c2007e-ae95-46ed-b6bd-97ff28a80fc4)

---

## Arithmetic Operations

* Addition
* Substraction
* Multiplication
* Division
* Dividsion(use // to get int value)
* Modulus(to get remainder)
* Exponent(which is the power)
* Assignment 
* Augmented Assignment operator

```
print(10+3)
print(10-3)
print(10*3)
print(10/3)

# to get int value
print(10//3)

#modulus
print(10 % 3)

#exponent which is power
print(10**3)

#assignment
x = 10
x = x+3
print(x)

#augmented assignment
x = 10
x += 3
print(x)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/63484d9e-cc98-46a7-ae7a-686244eff055)

---

## Operator Precedence

* Similar to mathematics , in programming to there is a order in which the operations are performed. 
* Order of operation is,
  -Exponential
  -Multiplication or Division
  -Addition or Substraction
 * Parenthesis() can be used to change the order of operation. It always overrides the order and is executed first.
 
```
x = 10+3*2**2
print(x)

x = (10+3)*2**2 #parenthesis used
print(x)
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/cd31b9c8-41f3-462f-8abd-f519cee79e5e)

---

## Math Functions

* round() a built in function to round off the value.
* abs() Absolute function is a built in function which gives positive value of any value given in input, even if the input value is negative.
* There are many other math functions.
math. is used to access these functions.
* To write programs with complex mathematical calculations we need to import the math module.
* A module in Python is seperate file with some reusable code.
* Modules are used to organise codes into different files.

> Note: You can search Python 3 math module to know more about functions in module.
[Module link](https://docs.python.org/3/library/math.html)

> math. used to access functions.
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/7b393323-7c3c-4b64-a200-a3064622a784)

```
import math
x = 2.9
print(round(x))

x = -2.9
print(abs(x))

print(math.ceil(2.9))

print(math.floor(2.9))
```

![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/0f0f9a28-c4e9-43bb-9cb9-05e32dd73d5e)

## If Statements

* If Statements help us to build programs that can make decisions based on some condition.
* If conditions are true the code block specified is executed else the otherwise block of code gets executed.

> Example

> If it's a hot then tell
    Its a hot day
    Drink plenty of water
 

> Otherwise if it's cold
    It's a cold day
    Wear warm clothes

 
> Otherwise
    It's a lovely day

```
is_hot = False
is_cold = True
if is_hot:
    print("It's a hot day")
    print("Drink plenty of water")
elif is_cold:
    print("It's a cold day")
    print("Wear warm clothes")
else:
    print("It's a lovely day")
print("Enjoy your day")
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/c748026d-f30d-4505-9630-239532ad2a11)

> Exercise
Price of house is $1M

> If buyer has good credit,
    they need to put down 10%

> Otherwise
    they need to put down 20%

> Print the down payment

```
#Exercise

price = 1000000
has_credit = True
if has_credit:
    down_payment = 0.1 * price
else:
    down_payment = 0.2 * price
print(f"Down Payment: ${down_payment}")
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/c1822e64-bef2-4720-974e-8a0ec947ac58)

---

## Logical Operators

This operator is used in situtaions with multiple conditions.

* AND-To combine condition and both must be True
* OR- To do certain things in situations where at least either of the condition is true.
* NOT-To inverse any boolean value.

```
#If the applicant has high income AND good credit
#Eligible for loan

has_high_income = True
has_good_credit = True
if has_high_income and has_good_credit:
    print("Eligible for loan")

#If the applicant has high income OR good credit
#Eligible for loan

has_high_income = True
has_good_credit = False
if has_high_income or has_good_credit:
    print("Eligible for loan")

#If applicant has good credit and doesn't have criminal record
#Eligible for loan

has_good_credit = True
has_criminal_record = False
if has_good_credit and not has_criminal_record:
    print("Eligible for loan")

has_good_credit = True
has_criminal_record = True
if has_good_credit and not has_criminal_record:
    print("Eligible for loan")
```
![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/020cd20b-4dc5-456b-935c-af8269e19441)














