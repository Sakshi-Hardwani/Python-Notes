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
 print(HelloWorld)
```
```
print("Sakshi Hardwani")
print("o----")
print(" ||||")
print("*"*10)
```



---

## Execution of Code

how code is executed in python which is line by line


---

## Variables
* integer
* float
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

```


---

## Receiving inputs
input() is used to take input 
contactination used to print two or more inputs


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
Example

Ask user their weight (in pounds), convert it to kg and print on terminal.

```
weight_lbs = float(input('What is your weight?(lbs): '))
weight_kg = weight_lbs * 0.45
print(weight_kg)
```
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

![image](https://github.com/Sakshi-Hardwani/Python-Notes/assets/117386798/170391c3-def6-45d0-86e4-abc89f4e4ea1)



---

## Formatted String

* Use to dynamically generate text with variables.
* With such contactinations it gets hard to visualise outputs
 Therefore,we use this concept of formatted strings.
* To define formatted string prefix your string with f
and use curly braces to dynamically insert values into string.

```
#To print such Sakshi [Hardwani] is a coder
first = 'Sakshi'
last = 'Hardwani'
#message = first + ' [' + last + '] is a coder ' #contactination method
msg = f'{first} [{last}] is a coder'#formatted string
print(msg)
```

![Screenshot (115)](https://hackmd.io/_uploads/ByC9oQ7Oa.png)


---

## String Methods

* len(): lenght of string 
* dot operator: to access the functions or methods, 
* e.g course.
* upper()
* lower()
* title()
* find(): to return index
* replace(): to replace
* in: to check string present or not , returned is a boolean value

```
course = 'Python for Beginners'
print(len(course)) #length of string
print(course.upper())
print(course.lower())
print(course.find('P')) #to return index
print(course.find('O')) #-1 is return index as there is no capital O i.e. it is case sensitive
print(course.find('Beginners')) #11 is return index as Beginners start from B
print(course.replace('Beginners', 'Absolute Beginners')) #to replace
print(course.replace('P', 'J'))
print('Python' in course)# to check string present or not , returned is a boolean value
print('python' in course)
```

![Screenshot (117)](https://hackmd.io/_uploads/rJ9DWE7ua.png)


---

## Arithmetic Operations

* Add
* Substarct
* Multiply 
* Divide
* Divide(// to get int value)
* Modulus(Remainder)
* Exponent(which is the power)
* Assignment 
* Augmented Assignment operator

```
print(10+3)
print(10-3)
print(10*3)
print(10/3)
print(10//3)# To get int value
print(10 % 3)
print(10**3)#exponent which is power
x = 10
x = x+3
print(x)
x = 10
x += 3#Augmented Assignment
print(x)
```
![Screenshot (119)](https://hackmd.io/_uploads/Hyzdh_Nua.png)









































