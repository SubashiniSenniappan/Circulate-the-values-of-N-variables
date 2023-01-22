# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function circulate. 
### Step 2: 
Take l and n as inputs.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using print function, print the results.
### Step 6: 
End the program.

## Program:
```py
#Program to circulate N values.
#Developed by:S.Subashini 
#RegisterNumber:22009344
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![reupload](https://user-images.githubusercontent.com/119404951/213900249-4b41bd4e-51c6-46d6-945d-19e8c03c8d7a.png)


## Result:
Thus, Using the function concept, circulating n variables are executed and displayed successfully.
