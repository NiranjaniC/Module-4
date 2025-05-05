# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
f=open("story.txt","r")
count=0
for lines in f:
    if lines [0] not in 'T':
        count+=1
print(count)
```
## Output

![image](https://github.com/user-attachments/assets/94ea7342-d7f8-4cbf-86a3-3f898f9151f9)


## Result
Thus the program has been executed successfully.
