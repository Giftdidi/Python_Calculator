# Python_Calculator
Introduction to Python week 1 Assignment

Instructions:

Basic Calculator Program

Create a simple Python program that asks the user to input two numbers and a mathematical operation (addition, subtraction, multiplication, or division).
Perform the operation based on the user's input and print the result.
Example: If a user inputs 10, 5, and +, your program should display 10 + 5 = 15.



ANSWER:


print("Select an operation to perform: ")
print ("1. ADD")
print ("2. SUBTRACT")
print ("3. MULTIPLY")
print ("4. DIVIDE")

operation = input()

if operation == "1":
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(" The sum is " + str(int(num1) + int(num2)))
elif operation == "2":
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(" The difference is " + str(int(num1) - int(num2)))
elif operation == "3":
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(" The product is " + str(int(num1) * int(num2)))
elif operation == "4":
    num1 = input("Enter first number: ")
    num2 = input("Enter second number: ")
    print(" The result is " + str(int(num1) / int(num2)))
else:
    print("Invalid Entry")





