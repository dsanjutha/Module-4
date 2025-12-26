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
my_dict = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'green',
    'orange': 'orange'
}
print("Original Dictionary:", my_dict)
sorted_by_keys = dict(sorted(my_dict.items()))
print("Dictionary Sorted by Keys:", sorted_by_keys)
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Dictionary Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="1137" height="355" alt="Screenshot 2025-12-26 190729" src="https://github.com/user-attachments/assets/e8b9c20c-c85f-4fe2-93ee-570d18291c66" />

## Result
The code executed successfully.
