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
# Step 2: Define dictionary
my_dict = {'a': 3, 'c': 1, 'b': 2, 'd': 4}

# Step 3: Sort by keys
sorted_by_keys = dict(sorted(my_dict.items()))

# Step 4: Sort by values
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Step 5: Display results
print("Original dictionary:", my_dict)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)

# Step 6: End of program
```

## Sample Output
```
Original dictionary: {'a': 3, 'c': 1, 'b': 2, 'd': 4}
Sorted by keys: {'a': 3, 'b': 2, 'c': 1, 'd': 4}
Sorted by values: {'c': 1, 'b': 2, 'a': 3, 'd': 4}
```

## Result
- Keys in alphabetical order
- Values in alphabetical order
  is verified

