# Maximum-value
Python program to find the maximum value in the given array of numbers
# Steps:
1.Declare a variable num to store array values
2.First set the first element in the array as max_value
3.Then use for loop for recursion
4.Compare max_value with next element,if it is greater than max_value set that element as max_value and continue until the end of array 
5.print the max_value
# code(maximum.py)
num=[10,6,89,54,33]
max_value=num[0]
for n in num:
    if n>max_value:
        max_value=n

print(max_value)

