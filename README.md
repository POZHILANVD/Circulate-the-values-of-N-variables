## DATE:
## EX:NO.2 Circulate the values of N variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get input from user using eval(input)
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using the concatination operation display the entire rotated list
### Step 6: 
stop the program
## Program:
```
# Developed by: POZHILAN V.D
# Register no: 212223240118
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![Screenshot 2024-08-25 154112](https://github.com/user-attachments/assets/e40a836b-11c0-4e16-af4f-6f923b401f80)
## Result:
Thus the program to circulate the values of N-variables have been executed successfully.
