Make a list `list1` with `10` integer elements.
- Print the 5th element from the list.
- Make a list `list2` from list1 that does not include the 0th, 4th, and 5th elements.
- What is the sum of all the items in the `list1` list (use the `sum()` builtin function).
- Sum only the elements from `list1` which are between the 2nd and the 6th elements.

list1=[i**1 for i in range(1,11)]
print(list1)
list2=list1[1:4]+list1[6:]
print(list2)
print(sum(list1))
print(sum(list1[1:7]))
