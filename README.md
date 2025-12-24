# assignment-1-part1-2-
ASSIGNMENT 1(PART1)

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 * num2
if num2 != 0:
    division = num1 / num2
else:
    division = "Undefined (division by zero)"

print("\nResults:")
print("Addition:", addition)
print("Subtraction:", subtraction)
print("Multiplication:", multiplication)
print("Division:", division)

#INPUT

Enter the first number: 23
Enter the second number: 43

#OUTPUT
Results:
Addition: 66.0
Subtraction: -20.0
Multiplication: 989.0
Division: 0.5348837209302325
PS D:\tutedude {Python}>

ASSIGNMENT 1(PART2)

first_name = input("Enter your first name: ")
last_name = input("Enter your last name: ")
full_name = first_name + " " + last_name
print("Hello,", full_name + "! Welcome.")

#INPUT

Enter your first name: Rahul
Enter your last name: Kumar

#OUTPUT

Hello, Rahul Kumar! Welcome.
