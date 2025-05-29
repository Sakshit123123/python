# Task 1: Check if a Number is Even or Odd

number = int(input("Enter an integer number: "))
if number % 2 == 0:
    print(f"The number {number} is Even.")
else:
    print(f"The number {number} is Odd.")
    
    
  # Task 2: Sum of Integers from 1 to 50 Using a Loop

total = 0
for i in range(1, 51):
    total += i
print(f"The sum of numbers from 1 to 50 is: {total}")
