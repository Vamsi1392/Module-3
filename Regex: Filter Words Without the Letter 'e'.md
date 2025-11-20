# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
fg= [word for word in items if not re.search('e', word)]
print(fg)
```

## Output

<img width="701" height="195" alt="Screenshot 2025-11-20 224619" src="https://github.com/user-attachments/assets/199d4dcf-d7d4-44ef-bd3d-91b383d4a865" />

## Result
Thus Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is executed successfully.
