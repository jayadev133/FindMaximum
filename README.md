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
Developed by: JAYADEV PALLINTI
RegisterNumber: 23007677
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: JAYADEV PALLINTI
RegisterNumber: 23007677
'''
def max_marks(marks):
   large=max(marks)
   return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: JAYADEV PALLINTI
RegisterNumber: 23007677 
'''
def max_marks(marks):
    large=max(marks)
    return large


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)
![Screenshot 2023-11-29 173745](https://github.com/jayadev133/FindMaximum/assets/150319465/a7bd5a9e-95b3-49e3-a69c-72dae4d84dc6)

ii)
![Screenshot 2023-11-29 173855](https://github.com/jayadev133/FindMaximum/assets/150319465/be0a47f9-8f9c-4cc2-9d72-d9dfd9944de1)

iii)
![Screenshot 2023-11-29 173955](https://github.com/jayadev133/FindMaximum/assets/150319465/966265fc-707c-4336-ae80-6e4f557af9e1)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
