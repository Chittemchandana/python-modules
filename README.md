# python-modules
# 1.math module approach1
import math
pie=math.pi
print("the value of pie: ",pie)

# approach2
from math import pi
print(pi)

# approach3
import math as m
result=m.sqrt(25)
print("square root of 25:",result)

# approach4
# importing * in python
from math import*
print(pi)
print(factorial(5))
print(sqrt(36))


# 2.random module approach1
import random
random_number=random.randint(1,10)
print("random number:",random_number)

# approach2
import random 
passlen=int(input("enter the length of password: "))
s="abcdefghikjlmnopqrstuvwxyzo1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
p="".join(random.sample(s,passlen))
print(p)

# 3.system module
import sys 
print(sys.path)
