# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
First step is to get inputs (a list and a integer) from the user
### Step 2: 
It iterates the given no. of times, each time performing the circulation operation.
### Step 3:
The first element of the list is removed and stored temporarily.
### Step 4: 
The removed element is appended to the end of the list.
### Step 5:
It displays the resulting list after circulation. 
## Program:
```python
def circulate():
    a=eval(input())
    b=int(input())
    for i in range(b):
        temp=a.pop(0)
        a.append(temp)
    print("After circulating the values are:",a)
```   
## Output:
![image](https://github.com/Visalan-H/Circulate-the-values-of-N-variables/assets/152077751/7753b9e5-63d1-4e69-9a7f-fef4c1f68fcf)

## Result:
Thus the outputs of the program are verified.
