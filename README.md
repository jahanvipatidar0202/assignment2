# assignment2
## task 1 and task2
task 1 is a basic Python script that prompts the user to enter a number and determines whether the number is even or odd. and task 2 is  a simple Python script that calculates and prints the sum of all numbers from 1 to 50 using a for loop.
## features
## task 1
1.The script asks the user to enter a number.

2.It converts the user input to an integer.

3.It checks if the number module 2 is zero .

4.If True, it prints that the number is even.

5.Otherwise, it prints that the number is odd.
## task 2
1.Initializes a variable sum to 0.

2.Iterates through numbers from 0 to 50 using range(51).

3.Adds each number to the sum.

4.Prints the final result.
## code task 1
number = int(input("Enter a number :"))
if number % 2 == 0:
    print( f"{number} is an even number")
else:
    print( f"{number} is an odd number")
## code task 2
sum =0
for i in range(51):
    sum += i
print(f"The sum of numbers from 1 to 50 is : {sum}")
