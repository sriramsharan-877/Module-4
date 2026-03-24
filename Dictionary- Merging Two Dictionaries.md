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
# Step 1: Define dictionaries
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

# Step 2: Define merge function
def merge(d1, d2):
    merged_dict = {**d1, **d2}
    return merged_dict

# Step 3: Call function and print result
result = merge(dict1, dict2)
print("Merged dictionary:", result)
```

## Output
```
Merged dictionary: {'a': 1, 'b': 20, 'c': 3, 'd': 4}
```

## Result
Python program that merges **two dictionaries** and combines their key-value pairs is verified.
