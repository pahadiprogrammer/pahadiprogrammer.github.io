---
layout: post
title: "Python101"
categories: tech
---

### What are Data Structures
Structures which are used to hold data. 

### Why data structures are needed
For storing a single unit of data like numbers, string a programming language provides data types - intger, string etc. But if want to store more than one instane of numbers then using variables is not optimal. For ex: If we know that we need to store 10 numbers then we can have 10 variables to hold them but it will be lot of effort to lets say create 100 variables to store 100 numbers. Also the numbers needed to be stored may also be dynamic in which case it's becomes more complicated. Hence data structures are needed which allow to hold multiple values of a type like numbers.

### What all data structures does python support
Common data structures in python that a developer should be aware of are
- List
- Dict

### List
It's used for holding data of different types. It is represented as `[data1, data2]`. It has no limit on size unless it's more than system's memory ;)
It can be n-dimesnional.

- ### One-dimensional(1D) List
1D list is represented as [data1, data2,.....]
List is 0-index which means the first element have index=0 and all subsequent elements are prevIndex+1.

The members of 1D can be accessed as shown below:
```
list = [1,2,3]
print(list[0]) -> Will print "1"
print(list[2]) -> Will print "3"

```

List is a mutable datatype which means it allows to edit it's content.
```
list = [1,2,3]
print(list[1]) -> Will print "2"
list[1] = 4
print(list[1]) -> Will print "4"
```

List can be traversed using a for-loop in python

```
list=[1,2,3]

for i in range(len(list)):
    print(list[i])

```

- ### Two-dimensional(2D) List
2D list is represented as [[data1], [data2],.....]. As can be seen it's a big-outer list and inside that there are number of 1-D lists. 

List is still 0-index which means the first element have index=0 and all subsequent elements are prevIndex+1. But if you want to access any element then it requires 2 index - (outer List Index) and (inner List index)

The members of 2D can be accessed as shown below:
```
list = [[1,2],[3,4],[5,6]]
print(list[0]) -> Will print "[1,2]"
print(list[0][0]) -> Will print "1"
```

In order to edit 2-D list
```
list = [[1,2],[3,4],[5,6]]
print(list[1]) -> Will print "2"
list[0][0] = 8
print(list[0]) -> Will print "[8,2]"
print(list[0][0]) -> Will print "8"
print(list[0][1]) -> Will print "2"
```

2-DList can also be traversed using a for-loop in python. But since it's 2D in nature it requires 2 for-loops to traverse

```
list = [[1,2],[3,4],[5,6]]

for i in range(3): -> will traverse the outer list which has length 3([1,2], [3,4], [5,6])
    for j in range(2)
    print(list[i][j]) -> will print 1,2,3,4,5,6 with each number in a new line
```