# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1.
Get the list of marks as input
### Step2. 
Use the sort() function or max() function or use the for loop to find the maximum mark.
### Step3. 
Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python

Program to mark the maximum of marks using the list method sort
Developed by: Rishi.M
RegisterNumber: 22000276

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
 
Program to find the maximum marks using the list method max().
Developed by: M.Rishi
RegisterNumber: 22000276

def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
 
Program to the maximum marks without using builtin functions.
Developed by: M.Rishi
RegisterNumber: 22000276

def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i > max1:
            max1=i
    return max1


```


## Output:
![OUTPUT](/1.jpg)
![OUTPUT](/2.jpg)
![OUTPUT](/3.jpg)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
