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
# Program to handle IndexError

my_list = [10, 20, 30, 40, 50]

try:
    index = int(input("Enter the index to access: "))
    print("Element at index", index, "is", my_list[index])

except IndexError:
    print("Error: Index is out of range!")

except ValueError:
    print("Error: Please enter a valid integer index.")
```
## Output
```
Enter the index to access: 2
Element at index 2 is 30
```

## Result
The output has been verified successfully.
