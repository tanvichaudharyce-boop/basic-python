# basic-python
#normal printing
print("Hello Tanvi \n welcome to the jupyter notebook")
#normal printing in multiple lines
print("Hello Tanvi \n welcome to the jupyter notebook")
Print("this is fun")
print("bye")
#printing using user input
a=input("enter your name")
print(f"Hi {a}\nwhat are you doing?")
#operators
a=10
b=20
print(f"addition of {a} and {b} is {a+b}")
print(f"substraction of {a} and {b} is {a-b}")
print(f"multiplication of {a} and {b} is {a*b}")
print(f"division of {a} and {b} is {a/b}")
print(f"double division of {a} and {b} is {a//b}")
print(f"power of {a} and {b} is {a**b}")
print(a is not b)
print(a>b)
print(a<b)
print(a>=b)
print(a<=b)
print(a==b)
print(a!=b)
#find the area of triangle
#you can also use 22/7 as pi's value
import math
pi=math.pi
r=float(input("enter radius for circle"))
area=pi*r*r
print(f"area of circle is {area}")
#find year,months and days using no.of days
n=392
y=n//360
r=n%360
m=r//30
d=r%30
print(f" {y} year {m} month {d} days")
#find hours,minutes and seconds using no .of seconds
n=123440
h=n//3600
r=n%3600
mi=r//60
sec=r%60
print(f"{h} hour {mi} minutes {sec} seconds")
