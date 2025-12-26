## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4, 'e': 5}
def merge(d1, d2):
    merged_dict = {**d1, **d2}
    return merged_dict
result = merge(dict1, dict2)
print("Merged Dictionary:", result)
```


## Output
<img width="1135" height="273" alt="Screenshot 2025-12-26 190558" src="https://github.com/user-attachments/assets/c5981dfc-ff0c-47fe-b4de-ba5278bdca36" />

## Result
The code is executed successfully.
