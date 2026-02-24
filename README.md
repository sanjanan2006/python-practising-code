# python-practice programs
boy_name=input("boy name: ")
girl_name=input("girl name: ")
boy_age=int(input("boy age: "))
girl_age=int(input("girl age: "))
age_diff=str(boy_age - girl_age)
print(f"{boy_name} loves {girl_name} age difference is {age_diff}")
## first and last number
'''python
first=input("enter your first name: ")
last=input("enter ypur last name: ")
print("full name is:",first +" "+ last)
'''
## cube of number
'''python
num=int(input("enter the number: "))
print("cube is:",num * num * num)
'''
## simple calculator
'''python
a=int(input("enter first number: "))
b=int(input("enter second number: "))
print("Addition",a+b)
print("Subtraction",a-b)
print("multiplication",a*b)            
'''

## concatenation of string
a="hello"
b="world"
c="python"
result=a+" "+b+" "+c
print(result)

## string manipulation methods
text="banana"
print(text.count("a"))

s=input()
print(s.replace(" ","-"))

s=input()
print(s.swapcase())

s=input()
print(len(s.split

## slicing of strings
text="python"
print(text[0:2])

text="programming"
print(text[::2])
print(len(text))
print(text[0:11:2])
print(text[1::3])
print(text[::-1])

## assignment operators
'''python
a=10
a+=100
print(a)

x=5
x-=3
print(x)

x=10
x//=3
print(x)

x=20
x**=2
print(x)

x=10
x%=5
print(x)

salary=int(input())
salary+=salary*0.20
print(int(salary))
'''


## repetition of string
'''python
symbol="*"
print(symbol*10)
    print(a*b)
'''
## comparision operator
a=20
b=50
print(a==b)
print(a>b)
print(a!=b)
print(a>=b)
