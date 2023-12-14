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
Program to mark the maximum of marks using the list method sort
Developed by: PRADEEP V 
RegisterNumber: 23013543
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: PRADEEP V
RegisterNumber:23013543 
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.

''' 
Program to the maximum marks without using builtin functions.
Developed by: PRADEEP V
RegisterNumber: 23013543
def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number>max):
            max=number
    return max
```


## Output:
![3 1](https://github.com/velupradeep/FindMaximum/assets/150329341/e50cadc9-2d2c-47dd-8f94-1ac6570281ca)
![3 2](https://github.com/velupradeep/FindMaximum/assets/150329341/a06de6fc-ad8e-43d8-beea-13d01ff18b8f)
![3 3](https://github.com/velupradeep/FindMaximum/assets/150329341/9c13d6be-2415-4876-b015-25d579fa65c4)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
