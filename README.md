count = int(input("Enter the count of numbers: "))

total = 0
for i in range(count):
    x = int(input("Enter an integer: "))
    total = total + x

avg = total / count
print("The average is:", avg)

Output:
Enter the count of numbers: 3
Enter an integer: 10
Enter an integer: 20
Enter an integer: 30
The average is: 20.0
# Python-56
Python program to find out the average of a set of integers
