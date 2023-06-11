# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Get the list of marks as input
### Step 2:
Use the sort() function or max() function or use the for loop to find the maximum mark.
### Step 3:
Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Gowrisankar.p
RegisterNumber: 212222230041
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Gowrisankar.p
RegisterNumber: 212222230041
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
'''
Program to the maximum marks without using builtin functions.
Developed by:GOwrisankar.p 
RegisterNumber: 212222230041
'''
def max_marks(list1):
    l=list1[0]
    for i in list1:
        if i>l:
            l=i
    return l        
```

## Output:

i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/gowrisankarponnusamy/FindMaximum/assets/119393123/a183e817-c76e-4ec0-a67c-27ac463d20a5)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/gowrisankarponnusamy/FindMaximum/assets/119393123/473a8b26-22e0-410e-beee-88d646911be6)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/gowrisankarponnusamy/FindMaximum/assets/119393123/c488b967-c2b9-4e29-8824-e24d41b84cc6)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
