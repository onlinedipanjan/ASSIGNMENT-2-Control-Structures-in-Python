# ASSIGNMENT 2: Control Structures in Python


# Task 1: Check if a Number is Even or Odd
# Problem Statement:  Write a Python program that:
# 1. 	Takes an integer input from the user.
# 2. 	Checks whether the number is even or odd using an if-else statement.
# 3. 	Displays the result accordingly.



odd_numebr = int(input("Enter the Number:- "))


if odd_numebr % 2 == 0:
    print("Even") 
else:
    print("Odd")  




# Task 2: Sum of Integers from 1 to 50 Using a Loop
 
# Problem Statement: Write a Python program that:
# 1.   Uses a for loop to iterate over numbers from 1 to 50.
# 2.   Calculates the sum of all integers in this range.
# 3.   Displays the final sum.



total_Number = 0

for num in range(1, 50):
     total_Number += num
     
print("The Sum of number from 1 to 50:", total_Number)
print(total_Number )




