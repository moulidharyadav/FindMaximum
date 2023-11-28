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
```Python

''' 
Program to mark the maximum of marks using the list method sort
Developed by: MOULIDHAR.G
RegisterNumber: 23009285
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: MOULIDHAR.G
RegisterNumber: 23009285
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: MOULIDHAR.G
RegisterNumber: 23009285
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/moulidharyadav/FindMaximum/assets/147078316/c43caabf-be2b-49a3-82ae-ec11f2619104)
![image](https://github.com/moulidharyadav/FindMaximum/assets/147078316/86d1b908-db9d-40d4-b44f-8febfaab84a5)
![image](https://github.com/moulidharyadav/FindMaximum/assets/147078316/47260705-9932-4893-8457-8e2ab5a9ad61)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
