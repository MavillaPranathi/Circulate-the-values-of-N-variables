# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
write the program in function syntax
### Step 2: 
assign the input values to the variables
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the both variables
### Step 6: 
the program ended
## Program:
```
#Program to circulate N values.
#Developed by:mpranathi
#RegisterNumber:22005710
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
!['OUTPUT'](/circulate.png)

## Result:
This programe is excuted successfully
