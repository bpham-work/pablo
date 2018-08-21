# Practice set 1

## Problem 1
Write a function named incrementList to add 1 to each integer in a given list

```python
list = [1, 2, 3]
incrementList(list)
print(list) # prints [2, 3, 4]
```

## Problem 2
Write a function named incrementNewList to add 1 to each integer in a given list and return a new list

```python
list = [1, 2, 3]
newList = incrementNewList(list)
print(newList) # prints [2, 3, 4]
```

## Problem 3
Write a function to check if a given list is sorted. It should return a boolean

```python
list1 = [1, 2, 3]
list1_result = isSorted(list1)
print(list1_result) # prints True

list2 = [3, 2, 1]
list2_result = isSorted(list2);
print(list2_result) # prints False

list3 = [5]
list3_result = isSorted(list3)
print(list3_result) # prints True

list4 = []
list4_result = isSorted(list4)
print(list4_result) # prints True
```

## Problem 4
Write a function to check if a given list is reverse sorted. It should return a boolean

```python
list1 = [1, 2, 3]
list1_result = isReverseSorted(list1)
print(list1_result) # prints False

list2 = [3, 2, 1]
list2_result = isReverseSorted(list2);
print(list2_result) # prints True

list3 = [5]
list3_result = isReverseSorted(list3)
print(list3_result) # prints True

list4 = []
list4_result = isReverseSorted(list4)
print(list4_result) # prints True
```

## Problem 5
Write a function to check if a given integer is prime. It should return a boolean

```python
print(isPrime(2)) # prints True
print(isPrime(0)) # prints False
print(isPrime(1)) # prints False
print(isPrime(10)) # prints False
```
