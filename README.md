DATE:
# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
first step is to define the function
### Step 2: 
get a,n inputs from the user
### Step 3: 
define the formula Get the value from the user for the number of rotation
### Step 4: 
print the result Using the slicing concept rotate the list
### Step 5: 
finally print the result**
## Program:
```
def circulate():
    global lst,n
    n = n % len(lst)
    rotated_list = lst[n:] + lst[:n]
    print(f"After circulating the values are: {rotated_list}")
lst=list(eval(input()))
n = int(input())

```

## Output:
![Screenshot 2024-10-05 200148](https://github.com/user-attachments/assets/90ccfe50-0530-4c09-8cc3-e492f9c2c035)


## Result:
By this program we able to circulate the values of n - variables

