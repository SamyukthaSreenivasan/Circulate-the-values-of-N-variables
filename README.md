# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the input from the user.
### Step 2: 
Create a function called circulate
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Circulate the input for given number of times.
### Step 6: 
End the program

## Program:
```
#Program to circulate N values.
#Developed by: Samyuktha.S
#RegisterNumber:22005276
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![output](/circulate)
## Result:

Thus the circulating n variables is successfully executed.
