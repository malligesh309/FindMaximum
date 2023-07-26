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
#Developed by:Malligesh M 
#RegisterNumber:23002936 

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
           max=i
    return max
```


ii)	# To find the maximum marks using the list method max().
```
#Developed by:Malligesh M 
#RegisterNumber:23002936

def max_marks(marks):
    n=max(marks)
    return n

```

iii) # To find the maximum marks without using builtin functions.

```
#Developed by:Malligesh M 
#RegisterNumber:23002936
    def max_marks(marks):
       max.sort()
       return marks[-1]
```

 

## Output:
![output](/Screenshot%20(9).png)
![output](/Screenshot%20(10).png)
![output](/Screenshot%20(11).png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.