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
Developed by: your name:Dinesh karthick.K.J
RegisterNumber: 22005847
'''
def max_marks(marks):
        marks.sort()
        return marks[-1]



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:Dinesh karthick.K.J
RegisterNumber: 22005847
'''
def max_marks(marks):
    large = max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:Dinesh karthick.K.J
RegisterNumber: 22005847
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i >max1:
            max1 = i
    return max1



```
## Sample Input and Output



## Output:
![4a1](https://user-images.githubusercontent.com/120552008/215006639-f5e3a567-662c-428a-ad2f-1c07a1a5d094.jpg)
![4a2](https://user-images.githubusercontent.com/120552008/215006659-20ae81ee-faa3-44c0-a5b1-bc291d5fbe4a.jpg)
![4a3](https://user-images.githubusercontent.com/120552008/215006669-de2288e6-b412-4ef7-97f7-5d63c2eae6d7.jpg)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
