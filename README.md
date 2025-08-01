# Excercise
1. Reverse string in text spacify on python have negative index:

**Code**
~~~python
text = "Hello Baby"
reverseText = ""
for index in range(1, len(text) + 1):
    reverseText += text[-index]
print(reverseText)
~~~
##### Output: `ybaB olleH`

2. Reverse string in text by use simple reverse:

**Code**
~~~python
text = "Hello Baby"
lastIndex = len(text) - 1
reverseText = ""
for index in range(len(text)):
    reverseText += text[lastIndex - index]
print(reverseText)
~~~
##### Output: `ybaB olleH`

3. Find index of Odd numbers in array:

**Code**
~~~python
arr = [5, 7, 8, 4, 3]
indexOfOdd = []
for i in range(len(arr)):
    if arr[i] % 2 == 1:
        indexOfOdd.append(i)
print(indexOfOdd)
~~~
##### output: `[0, 1, 4]`

4. Find average of numbers in list:

**Code**
~~~python
arr = [5, 7, 8, 4, 3]
average = 0
sum = 0
for value in arr:
    sum += value
average = sum / len(arr)
print(average)
~~~
##### Output: `5.4`
5. Find value of name array dictionary one by one:

**Code**
~~~python
arr = [
    {'name': 'bopha', 'age': 18},
    {'name': 'thida', 'age': 12},
    {'name': 'kanha', 'age': 16},
]
for dicts in arr:
    print(dict['name'])
~~~
##### Output:
##### `bopha`
##### `thida`
##### `kanha`

6. Find sum numbers in array:

**Code**
~~~python
arr = [5, 7, 8, 4, 3]
sum = 0
for value in arr:
    sum += value
print(sum)
~~~
##### Output: `27`

7. Find even numbers in array:

**Code**
~~~python
arr = [5, 7, 8, 4, 3]
for value in arr:
    if value % 2 == 0:
        print(value)
~~~
##### Output: `8 4`

8. Find Minimum of numbers in array:

**Code**
~~~python
arr = [10, 40, 20, 4, 3]
min = arr[0]
for value in arr:
    if value < min:
        min = value
print(min)
~~~
##### Output: `3`
9. Move number one to one step to right:

**Code**
 ~~~python
 arr = [0, 0, 1, 0, 0]
 isFound = False
 for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i + 1] = 1
        isFound = True
print(arr)
 ~~~
 ##### Output: `[0, 0, 0, 1, 0]`
10. Move number one to one step to left:

**Code**
~~~python
arr = [0, 0, 1, 0, 0]
isFound = False
for i in range(len(arr) - 1):
    if arr[i] == 1 and not isFound:
        arr[i] = 0
        arr[i - 1] = 1
        isFound = True
print(arr)
~~~
##### Output: `[0, 1, 0, 0, 0]`

11. Find Maximum of numbers in array:

**Code**
~~~python
arr = [10, 40, 20, 4, 3]
max = arr[0]
for value in arr:
    if value > max:
        max = value
print(max)
~~~
##### Output: `40`
12. Sum value in row array2D:

**Code**
~~~python
arr2D = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9],
]
sum = 0
arr = []
for row in range(len(arr2D)):
    for col in range(len(arr2D[row])):
        sum += arr2D[row][col]
    arr.append(sum)
    sum = 0
print(arr)
~~~
##### Output: `[6, 15, 24]`