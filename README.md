# python-project
import math 
print(""" 
press -  
1 - Addition(x, y) 
2 - subtraction(x,y) 
3-multiplication(x,y) 
4 - division(x, y) 
5- exponent(x, y) 
6 - tan(x, y) 
7 - sin(x) 
8 - cos(x) 
9 - factorial(x) 
10 - log(x)
11 - x^2
12 - x^3
13 - x^n
14 - root(x)
15 - percentage(x out of y)

""") 
n = input("") 
if n == "1": 
    x = int(input("1st number -")) 
    y = int(input("2nd number -")) 
    print(x + y) 
elif n == "2": 
    x = int(input()) 
    y = int(input()) 
    print(x-y) 
elif n == "3": 
    x = int(input()) 
    y = int(input()) 
    print(x*y) 
elif n == "4": 
    x = int(input()) 
    y = int(input()) 
    print(x/y) 
elif n == "5": 
    x = int(input()) 
    y = int(input()) 
    print(x**y) 
elif n == "6": 
    x = int(input()) 
    print("in radians",math.tan(x)) 
elif n == "7": 
    x = int(input()) 
    print("in radians",math.sin(x)) 
elif n == "8": 
    x = int(input()) 
    print("in radians",math.cos(x)) 
elif n == "9": 
    x = int(input()) 
    print(math.factorial(x)) 
elif n == "10": 
    x = int(input()) 
    print(math.log(x)) 
elif n == "11":
    x = int(input())
    sq=x**2
    print(sq)
elif n == "12":
    x = int(input())
    cube=x**3
    print(cube)
elif n == "13":
    x = int(input())
    n1 = int(input())
    a = x**n1
    print(a)
elif n == "14":
    x = int(input())
    root = x**1/2
    print(root)
elif n == "15":
    x = int(input())
    y = int(input())
    per = (x/y)*100
    print(per,"%")
    GOOD
