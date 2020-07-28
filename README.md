# PythonCodePractice

# Legal Variable names

myvar = "Jesse"
my_var = "Jesse"
_My_Var = "Jesse"
MyVar = "Jesse"
MYVAR = " Jesse"
myvar2 = "Jesse"

print(MYVAR)

# Datatypes

i = 5 # Integer datatype
f = 3.5# Float datatype
c = 3j# complex datatype

print(type(i))
print(type(f))
print(type(c))

#Converting datatypes

a = float(i)
print(a)

b = int(f)
print(b)

MyAge = 26
print("Hi, my name is Natalie and I am " + str(MyAge) + " years old.")

#Arrays + Slicing

cars = ["Toyota", "Honda", "Opel", "Mercedes", "BMW"]
print(cars[1])
print(cars[1:4])
print(cars[-5:-1])

Name = "Natalie"
print(Name[0:5])
print(len(Name))

whitespaces = "   Test     "
print(whitespaces)
print(whitespaces.strip())

print(Name.upper())
print(Name.lower())

print(whitespaces.strip().lower())
print(whitespaces.strip().upper())

n = "Hello Natalie"
print(n)
print(n.replace("Hello", "Bye - Bye"))

phrase = "Betty bought butter but the butter was bitter so betty bought better butter to make the bitter butter better"

phrase = "tt" in phrase
print(phrase)

#If Statements

a = 300
b = 10
if b > a:
    print("b is greater than a!")
else:
    print("a is greater than b")

if a > b: print("a is bigger than b!")

elif a == b:
    print(" a & b are equal")
else:
    print("a & b are NOT equal!")

q = 200
r = 33
s = 500
if q > r and s > q:
    print("Both conditions are true")
if  q > r or q > s:
    print("One condition is true")

#Nested if Statement

e = 41
if e > 10:
    print("The number is above 10")
    if e > 20:
        print("This number is also above the number 20")
    else:
        print("Not above 20!")

#While-loops

i = 1
while i < 6:
    print(i)
    i = i + 1

v = 1
while v < 10:
    print(v)
    if v == 3:
        break
    v = v + 1

w = 1
while w < 5:
    if w == 4:
        continue
    w = w + 1
    print(w)

T = 1
while T < 8:
    print(i)
    T = T + 1
else:
    print("i is no longer less than 7") # 5 is not popping up!!!

#Array
cars = ["Mazda", "Honda", "Opel", "Toyota", "BMW"]
print(cars[1])
cars.append("Mercedes")
print(cars)
cars.pop(2)
print(cars)
print(cars.index("Mercedes"))

#For loops
fruits = ["Apples", "Banana", "Cherry"]
for a in fruits:
    print(a)
for a in fruits:
    print("Fresh "  + a)

a = ["Tasty", "Red", "Sweet"]
b = ["Apple","Banana", "Cherry"]
for x in a:
    for y in b:
        print(x,y)
if "Strawberries" in fruits:
    print("yes, we have this item available")
else:
    print("Sorry, This item is not available")

#Dictionaries

CAR = {
    "Brand": "Honda",
    "Model": "Civic",
    "Year" : 2020
}
print(CAR)
print(CAR["Brand"])
CAR["Year"] = 2017
print(CAR)
CAR["Colour"] = "Silver"
print(CAR)

for Z in CAR:
    print(Z)
for X in CAR:
    print(CAR[X])
print(len(CAR))

#Nested Dictionary

nails = {
    "hands": {
       "tips1": "gel",
        "tips2": "Acrylic",
        "tips3": "powder acrylic"
    },
    "toe nails": {
        "toenails1": "buff and polish",
        "toenails2": "file nails",
        "toenails3": "colour polish"
    },
}
print(nails)

# Arithmetic Operators

x = 10
y = 20
print('x + y =', x + y)
print(x + y)

x = 10
y = 5
print('x - y =', x - y)
print(x - y)

x = 5
y = 10
print('x * y =', x * y)
print(x * y)

x = 10
y = 2
print('x / y =', x / y)
print(x / y)

x = 20
y = 6
print('x // y =', x// y)
print(x // y)

x = 3
y = 5
print('x ** y =', x ** y)
print(x ** y)

x = 10
y = 12

print("x < y", x > y)
print(x > y)
if x > y:
    print("x is greater than y")
else:
    print("y is greater than x")

print('x == y', x == y)
print(x == y)

print('x != y', x != y)
print(x != y)

print('x >= y is', x >= y)
print(x >= y)

x = "True"
y = "False"
print("x and y is ", x and y)
print(x and y)

print("x or y is ", x or y)
print(x or y)

print("not x is ",not x)
print(not x)

#is and is not operator

x1 = 5
y1 = 5
x2 = "Hello"
y2 = "Hello"
x3 = [1, 2, 3]
y3 = [1, 2, 3]
print(x1 is not y1)

print(x2 is y2)

print(x3 is not y3)####DEBUG

a = "Hello Team"
y = {1: "a", 2: "b"}

print("H" in a)
print(1 in y)
print("a" in y)
print("a" in y[1])

a = "false"
b = "true"
variable1 = 100

if variable1:
    print("1 got a true expression value")
    print(variable1)
else:
    print(" 1 got a false expression value")
    print(variable1)

variable2 = 199
if variable2 == 200:
    print("equals to or the same as 199")
    print(variable2)
elif variable2 == 100:
    print("equals to or the same as 100")
    print(variable2)
else:
    print("the number is 199")
var1 = float(input("please enter a number"))

#nested if statement

var = float(input("please enter a number between 1 & 10 "))
print(var)
if var >= 0:
    if var == 0:
        print("Zero")
    else:
        print("Positive number entered")
else:
    print("Negative number entered")

#Compound Condition
number1 = 100
number2 = 1000
number3 = 10000
if number2 > number1 and number2 < number3:
    print("number two is in the middle")
if number1 > number3 or number1 < number2:
    print("one condition is true")

#While loop

count = 1
while count < 11:
    print("the count is " + str(count))
    count += 1

i = 0
a = "Natalie"
while i < len(a):
    print("current letter is : " + a[i])
    i += 1

while i < len(a):
    if a[i] == 'i' or a[i] == 't':
        i += 1
        continue
    print("Current letter is: " + a[i])
    i += 1

while i < len(a):
    if a[i] == 'i' or a[i] =='t':
        i += 1
        break
    print("current letter is: " + a[i])
    a += 1
print("Hello, i am outside of the loop")

while i <len(a):
    i += 1
    pass
print("value of i: " + str(i))

alphabet = ["a", "b", "c", "d"]
count = 1
innerCount=1

while count < 5:
    while innerCount < len(alphabet):
        print(str(count) + alphabet[innerCount])
        innerCount += 1
    count += 1
    innerCount = 1
def Natz_function():
    print("Natz says hello")
Natz_function()
def printFnameLname(Fname, Lname):
    print(Fname + " " + Lname)
printFnameLname("Natalie", "TT")
def printcolours(*colours):
    print("the first coclour is: " + colours[0])
def doubled(num):
    return 2*num
print(doubled(3))
print(doubled(5))
print(doubled(9))
def send_email():
    pass
print("Test to ensure pass statement has been executed")

prices = {
    'eggs': 3.50,
    'bread': 4.50,
    'chips': 5.50
}
print(prices)

fruits = ["Apples", "Banana", "Pear"]
Cost = [2.88, 3.78, 8.45]
fruits_dictionary = dict(zip(fruits, Cost))
print(fruits_dictionary)
