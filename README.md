# Simple_Calculator
#Creating a simple calculator for arithmetic operations for two numbers.
print("SIMPLE CALACULATOR")
print("Enter the first number: ")
num1 = int(input())
print("Enter the second number: ")
num2 = int(input())
ch=0
while ch<5:
  print("1.addition")
  print("2.subtraction")
  print("3.multiplication")
  print("4.division")
  print("5.exit")
  print("Enter your choice: ")
  ch=int(input())
  if ch==1:
    print("Addition of two numbers:",num1+num2)
  elif ch==2:
    print("Subtraction of two numbers:",num1-num2)
  elif ch==3:
      print("Multiplication of two numbers:",num1*num2)
  elif ch==4:
        print("Division of two numbers:",num1/num2)
  elif ch==5:
        print("Exit")
        break
  else:
    print("Invalid choice")
