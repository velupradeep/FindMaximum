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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: PRADEEP V 
RegisterNumber: 23013543
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: PRADEEP V
RegisterNumber:23013543 
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: PRADEEP V
RegisterNumber: 23013543
'''
def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number>max):
            max=number
    return max
```


## Output:
1.![3 1](https://github.com/velupradeep/FindMaximum/assets/150329341/4f7efa84-2bcd-446b-b523-91205268f9ab)
2.![3 2](https://github.com/velupradeep/FindMaximum/assets/150329341/46d04164-5944-4e2b-873a-70014d8a7eaa)
3.![3 3](https://github.com/velupradeep/FindMaximum/assets/150329341/7542a243-0e2c-43c6-a767-0a20108b459f)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
