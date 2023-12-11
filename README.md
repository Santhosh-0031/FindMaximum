# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the  maximum of marks using the list method sort
Developed by: santhosh kumar R
RegisterNumber: 23013562

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to mark the  maximum of marks using the list method sort
Developed by: santhosh kumar R
RegisterNumber: 23013562

def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```
Program to mark the  maximum of marks using the list method sort
Developed by: santhosh kumar R
RegisterNumber: 23013562

def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number>max):
            max=number
    return max

```
## Sample Input and Output

## Output:
1.
![Screenshot 2023-12-11 213245](https://github.com/Santhosh-0031/FindMaximum/assets/145551108/8d056ea9-b315-4c7c-bbc8-aa88007cbe28)

2.
![Screenshot 2023-12-11 213306](https://github.com/Santhosh-0031/FindMaximum/assets/145551108/05383220-5ee8-4c66-b45d-d59585072e76)

3.
![Screenshot 2023-12-11 213320](https://github.com/Santhosh-0031/FindMaximum/assets/145551108/71d6e4f3-fab3-4afa-8483-7f6dca14fbac)

 ## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
