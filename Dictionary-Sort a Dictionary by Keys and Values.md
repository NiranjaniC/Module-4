# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
dictionary1 = {1: 2, 5: 12, 6: 18}
dictionary2 = {4: 24, 2: 56, 3: 323}
merged_dict = {**dictionary1, **dictionary2}
sorted_by_value = sorted(merged_dict.items(), key=lambda item: item[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_by_value)
```

## Sample Output

![image](https://github.com/user-attachments/assets/2fdd4f45-4879-46c2-a917-ca2ad214cb4b)


## Result
Thus the program has been executed successfully.

