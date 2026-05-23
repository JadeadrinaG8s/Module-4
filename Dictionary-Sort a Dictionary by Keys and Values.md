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
Add Code here
```
d = {'b': 20, 'a': 10, 'c': 15}

print("Original Dictionary:", d)

sort_keys = dict(sorted(d.items()))
print("Sorted by Keys:", sort_keys)

sort_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by Values:", sort_values)
```

## Sample Output
```
Original Dictionary: {'b': 20, 'a': 10, 'c': 15}
Sorted by Keys: {'a': 10, 'b': 20, 'c': 15}
Sorted by Values: {'a': 10, 'c': 15, 'b': 20}
```
## Result
thus the program was successfull
