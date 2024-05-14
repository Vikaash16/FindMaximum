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
#TO DEVELOP A PROGRAM TO FIND THE MAXIMUM OF MARKS USING THE LIST METHOD SORT
#DEVELOPED BY: Vikaash P
#REGISTER NUMBER: 212223240180

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
#TO DEVELOP A PROGRAM TO FIND THE MAXIMUM OF MARKS USING THE LIST METHOD max()
#DEVELOPED BY: Vikaash P
#REGISTER NUMBER: 212223240180

def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
#TO DEVELOP A PROGRAM TO FIND THE MAXIMUM OF MARKS WITHOUT USING BUILTIN FUNCTIONS
#DEVELOPED BY: Vikaash P
#REGISTER NUMBER: 212223240180

def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark



```



## Output:
![image](https://github.com/Vikaash16/FindMaximum/assets/139218414/fc44177e-7846-41ce-a46f-4183cf43f3da)

![image](https://github.com/Vikaash16/FindMaximum/assets/139218414/655edb0c-7b1a-453b-a654-acc0cde397c0)

![image](https://github.com/Vikaash16/FindMaximum/assets/139218414/49ab00a8-ea9b-4481-af82-fb16fb102fa1)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
