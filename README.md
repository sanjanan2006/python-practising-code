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
'''python
a=20
b=50
print(a==b)
print(a>b)
print(a!=b)
print(a>=b)
'''
## logical and membership operator
'''python
marks = 85
subjects =["maths","science","english"]
print(marks>90 and "maths" in subjects)
'''
## bitwise operator
'''pyhton
a=5
b=3
print(a&b)
print(a|b)
print(a^b)
'''
## list and it's types(methods)
'''python
list=[1,"bru",True,[1,2,3]]
print(list)

list=["bru","sugar","milk"]
list.pop()
print(list)
list.remove("sugar")
print(list)
list.append("chicken")
print(list)
list.insert(1,"muton")
print(list)
list[0]="coffee powder"
print(list)
'''
## slicing of list
'''python
l=[0,2,4,6,8,9]
print(l[::2])
print(l[0:5])
print(l[2:6:2])
print(l[:2])
print(l[3:])
print(l[-4:-1])
print(l[::-2])
'''
## functions of list
'''python
items=["bru","sugar","milk"]
print(len(items))
l=[1,24,13,40,5]
print(sum(l))
print(items.index("bru"))
n=[1,2,1,4,1,6,7]
print(n.count(1))
print(l.reverse())
print(sorted(l))

matrix=[[1,2,3],[4,5,6],[7,8,9]]
print(matrix[0])
print(matrix[2])
'''
## list comphrensions
'''python
sqaures=[x*x for x in range(5)]
print(sqaures)

nums=[5,4,8,4,5]
print(len(nums))
print(max(nums))
print(min(nums))
nums.sort()
print(nums)
'''
## tuples examples
'''python
t=(10,"sanju",3.5,True)
print(t)

t=(10,)
print(t)

t=5,8,9
## tuples operations and methods
'''python
# concatenation 
t1=(1,2,3,4)
t2=(5,6,7,8)
result=t1+t2
print(result)
# repetation
t=(1,4)
print(t*4)
# membership
t=(10,20,30)
print(20 in t)
print(10 not in t)
# tuple length
t=(1,2,3,4,5,6,)
print(len(t))
# finding minimum and maximum
t=(8,3,12,6)
print(min(t))
print(max(t))
# counting elements
t=(1,3,5,3,)
print(t.count(3))
# finding index of element
t=("apple","mango","banana")
print(t.index("mango"))
'''
# creating set 
'''python
numbers={1,2,3,4}
print(numbers)

# set automatically removes duplicates
numbers={1,3,4,3,3}
print(numbers)
'''
# add element
'''python
fruits={"apple","banana"}
fruits.add("orange")
print(fruits)
# removing an element
fruits={"apple","cherry","banana","mango"}
fruits.remove("cherry")
print(fruits)
# set operations
A={1,2,3}
B={3,5,6}
print(A|B) #union
print(A&B) #intersection
print(A-B) #differnce
# length of set
numbers={1,2,3,4}
print(len(numbers))
# no indexing
numbers={1,2,3}
print(numbers[0])
'''
'''python
my_dict={
    "name":"sanjana",
    "age":20,
    "weight":20.5,
}
print(my_dict)

# accessing values
student={
    "course":"python",
    "name":"sanju",
    "age":20,
}
print(student["name"])

# adding a new item
student={
    "name":"sanju",
    "age":20,
}
student["course"]="python"
print(student)

# updating a value
student={
    "name":"sanju",
    "age":20,
}
student["age"]=21
print(student)

# nested dictionary

student={
    "name":"sanju",
    "marks":{"math":90,"science":85}
}
print(student["marks"]["math"])
'''
## dictonary methods
'''python
# keys()
student={"name":"sanjana","age":20,"course":"python"}
print(student.keys())
#values()
student={"name":"sanjana","age":20,"course":"python"}
print(student.values())
# pop()student={"name":"sanjana","age":20,"course":"python"}
student.pop("course")
print(student)
# itmes()
student={"name":"sanjana","age":20,"course":"python"}
print(student.items())
# get()
student={"name":"sanjana","age":20,"course":"python"}
print(student.get("name"))
# update()
student={"name":"sanjana","age":20,"course":"python"}
student.update({"age":21})
print(student)
# popitem()
student={"name":"sanjana","age":20,"course":"python"}
student.popitem()
print(student)
# clear()
student={"name":"sanjana","age":20,"course":"python"}
student.clear()
print(student)
'''
print(student([s1][name]))
'''
