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
Developed by: Swaminathan V
RegisterNumber: 23000747

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python

Program to find the maximum marks using the list method max().
Developed by: Swaminathan V
RegisterNumber: 23000747

def max_marks(marks):
    large = max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
 
Program to the maximum marks without using builtin functions.
Developed by: Swaminathan V
RegisterNumber: 23000747

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![3A-CA-01](https://github.com/SwaminathanV23000747/FindMaximum/assets/148931113/ecf7e693-df47-4d72-83d3-72294daaa65b)

![3A-CA-02](https://github.com/SwaminathanV23000747/FindMaximum/assets/148931113/a4661550-e015-495b-a0ea-d890efc7734b)

![3A-CA-03](https://github.com/SwaminathanV23000747/FindMaximum/assets/148931113/0080521d-c451-4c96-8aa3-1f77a02a4e4d)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
