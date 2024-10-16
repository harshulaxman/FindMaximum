## DATE:
# EX-6: Find the maximum of a list of numbers
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
#devoloped by : harsshitha lakshmanan
#Register num : 212223230075
def max_marks(array):
    array.sort()
    return array[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
#developed by: Harsshitha lakshmanan
#register number:212223230075

def max_marks(array):
    return max(array)


```

iii) # To find the maximum marks without using builtin functions.
```Python
#developed by: Harsshitha lakshmanan 
#register number:212223230075

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1


```



## Output:
![image](https://github.com/user-attachments/assets/0ccc568b-80da-4eb7-a86c-ea4631b52ac9)
![image](https://github.com/user-attachments/assets/89df70b7-f26e-4a7e-be5a-d5c0c07d25cc)
![image](https://github.com/user-attachments/assets/a94821f3-bae7-4baf-ba90-26b6460ce796)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
