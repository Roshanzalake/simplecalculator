def add(num1,num2):
    return num1+num2

def  subtrct(num1,num2):
    return num1-num2

def  multiplication(num1,num2):
    return num1*num2

def divide(num1,num2):
    
    return num1/num2

num1=float(input("Enter your first number"))
choice=input()
num2=float(input("ENTER your second number"))

if choice=='+':
    print(add(num1,num2))

if choice=='-':
    print(subtrct(num1-num2))

if choice=='*':
    print(multiplication(num1,num2))

if choice=='/':
    if num2!= 0:
     print(divide(num1,num2))
    else:
        print(" second number is not be  0")

print(" This is your calculation ")        


    
    
