#Calculate Factorial Using a Function
def Factorial(Number): if Number==0: 
                       return 1 
                      else: return Number*Factorial(Number-1) 
Number=int(input("Enter a number:"))
print(Factorial(Number))

#Using the Math module for calculations 
import math
Number=int(input("Enter a number:")) 
SRoot=math.sqrt(Number)
Logarithm=math.log(Number) 
Radian=math.sin(Number)
print(f"Square root of {Number} is {SRoot}")
print(F"Logarithm of {Number} is {Logarithm}")
print(f"Sin of {Number} is {Radian}")
