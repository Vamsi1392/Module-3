# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
def createlist(n):
    l=[]
    for i in range(1,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list = ",sum(l))
```

## Output
<img width="1070" height="278" alt="Screenshot 2025-11-20 224419" src="https://github.com/user-attachments/assets/4cd6583e-5206-4749-ae77-50b1329b87f4" />

## Result
Thus Python program to calculate the sum of all even elements in a list is executed successfully.
