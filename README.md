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
#Program to mark the maximum of marks using the list method sort.
#Program Developed by: Tom Francies Xaviour
#Register No:212223110060

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Program Developed by: Tom Francies Xaviour
#Register No:212223110060
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
#Program to find the maximum marks without using builtin functions.
#Program Developed by: Tom Francies Xaviour
#Register No:212223110060
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark


```



## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Tomfx03/FindMaximum/assets/101335832/e1f1575c-870b-408a-b0d1-1370ba6016f1)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Tomfx03/FindMaximum/assets/101335832/105efb72-f7bd-40cd-932d-b30ecca31b68)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Tomfx03/FindMaximum/assets/101335832/d29e8e12-2f2a-485d-ae8b-03909ad0b338)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
