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
# Program to sort dictionary keys and values

my_dict = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'green',
    'orange': 'orange'
}

# Sort keys alphabetically
sorted_keys = sorted(my_dict.keys())

# Sort values alphabetically
sorted_values = sorted(my_dict.values())

print("Dictionary:", my_dict)
print("Keys in alphabetical order:", sorted_keys)
print("Values in alphabetical order:", sorted_values)
```
## Sample Output
```
Dictionary: {'banana': 'yellow', 'apple': 'red', 'grape': 'green', 'orange': 'orange'}

Keys in alphabetical order:
['apple', 'banana', 'grape', 'orange']

Values in alphabetical order:
['green', 'orange', 'red', 'yellow']
```
## Result
The output has been verified successfully.

