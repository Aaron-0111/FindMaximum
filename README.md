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
Developed by: Aaron Rajesh R
RegisterNumber: 23008897
'''
def max_marks(marks):
    marks.sort()
    b=marks[-1]
    return b


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Aaron Rajesh R
RegisterNumber: 23008897
'''
def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
'''
Program to the maximum marks without using builtin functions.
Developed by: Aaron Rajesh R
RegisterNumber: 23008897
'''
def max_marks(list1):
    for i in list1:
        if i>94:
            return i


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-31 230403](https://github.com/Aaron-0111/FindMaximum/assets/149347631/34af8ed3-408e-49ac-a334-22dfcafc30bc)
![Screenshot 2023-12-31 231119](https://github.com/Aaron-0111/FindMaximum/assets/149347631/9b9937bf-1a56-4611-ba67-c6fc4a64db50)
![Screenshot 2023-12-31 231955](https://github.com/Aaron-0111/FindMaximum/assets/149347631/155cacec-653d-48da-b060-5ebf41d00a28)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
