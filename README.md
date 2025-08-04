# Week2-Python
Python List
# 🐍 Python List Operations Example

This Python script demonstrates fundamental list operations, including appending, inserting,
extending, popping, sorting, and retrieving the index of a specific element.

## 📄 Code Overview

```python
my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
my_list.insert(1, 15)
my_list.extend([50, 60, 70])
my_list.pop()
my_list.sort()
index_30 = my_list.index(30)
print(index_30)

🔧 What It Does
Creates an empty list.
Appends integers 10, 20, 30, and 40.
Inserts 15 at index 1.
Extends the list with [50, 60, 70].
Pops the last item (70).
Sorts the list in ascending order.
Finds the index of value 30 and prints it.

✅ Final Output
After all operations, the final list is:
[10, 15, 20, 30, 40, 50, 60]
And the printed output will be:
3
The value 30 is at index 3 after sorting.


