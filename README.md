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
```
```
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```

def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number>max):
            max=number
    return max
```


## Output:

![max1](https://github.com/velupradeep/FindMaximum/assets/150329341/7c2fa357-094d-4f0e-84ca-093672bf0b10)
![max2](https://github.com/velupradeep/FindMaximum/assets/150329341/17501117-79e0-4b19-bef0-47af9b942aa9)
![max3](https://github.com/velupradeep/FindMaximum/assets/150329341/9a8f3610-d4c7-4d17-aa1c-ac3067d960e2)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
