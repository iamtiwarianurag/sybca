# Factorial Number Program

## The factorial of a number is the product of all the numbers from 1 to that number.

### In this program I have Take a user input of an interger number and the program will give me factorial of that number as output.

**In very first If conditon i have make sure to check the given input, if the given input is less than 1 it will give a message**

---
The Code is:
___
```
num = int(input("Enter The Number : "))
factorial = 1
if num < 0:
   print("Sorry, factorial does not exist for negative numbers")
elif num == 0:
   print("The factorial of 0 is 1")
else:
   for i in range(1,num + 1):
       factorial = factorial*i
   print("The factorial of",num,"is",factorial)
```

**Output**
