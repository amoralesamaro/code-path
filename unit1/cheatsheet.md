# Unit 1 Cheatsheet

## 1. print()
`print(value)` prints text, numbers, or variables to the console.

Example:
```
print("Hello")
print(5)
```

## 2. len()
`len(obj)` returns the length of a list or string.

Example:
```
print(len([1, 2, 3]))  # 3
print(len("abc"))    # 3
```

## 3. range()
`range(start, stop, step)` generates a sequence of numbers.

Example:
```
for i in range(5):
    print(i)  # 0,1,2,3,4

for i in range(1, 6):
    print(i)  # 1,2,3,4,5
```

## 4. if / elif / else
Use conditionals to choose between different actions.

Example:
```
x = 3
if x < 0:
    print("negative")
elif x == 0:
    print("zero")
else:
    print("positive")
```

## 5. for loops
Loop over items in a list or numbers in a range.

Example:
```
numbers = [1, 2, 3]
for num in numbers:
    print(num)
```

## 6. list append
`lst.append(item)` adds an item to the end of a list.

Example:
```
lst = [1, 2]
lst.append(3)
print(lst)  # [1, 2, 3]
```

## 7. list sort
`lst.sort()` sorts a list in ascending order.

Example:
```
lst = [3, 1, 2]
lst.sort()
print(lst)  # [1, 2, 3]
```

## 8. list indexing
`lst[index]` gets an item from a list using zero-based indexing.

Example:
```
lst = ["a", "b", "c"]
print(lst[0])  # a
print(lst[-1]) # c
```

## 9. list slicing
`lst[start:end]` returns a new list from start up to but not including end.

Example:
```
lst = [0, 1, 2, 3, 4]
print(lst[1:4])  # [1, 2, 3]
```

## 10. Optional useful methods
- `lst.insert(i, item)` inserts an item at index `i`
- `lst.remove(item)` removes the first matching item
- `lst.pop(i)` removes and returns the item at index `i`
- `lst.copy()` returns a shallow copy of the list
- `abs(x)` returns the absolute value of `x`
- `enumerate(lst)` returns pairs of index and value
