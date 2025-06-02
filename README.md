
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class Saveetha:
    def __init__(self, r):
        self.area = math.pi * (r ** 2) 
    def slot(self):
        print("Area of circle:", round(self.area, 2))
r = float(input())
res = Saveetha(r)  
res.slot()
```


## Output
![447278315-bcbed6ad-9fd0-45ca-926d-63ebbb5210fd](https://github.com/user-attachments/assets/a523cac6-2cd2-4c2d-9051-4c8306b7f0db)

## Result
Thus,the program has been executed successfully.


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
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```


## Output

![447278628-5e9609b9-3757-4236-8ae9-fb8858daa0c6](https://github.com/user-attachments/assets/f4ed4424-a561-4740-8d84-5a27082d00b1)


## Result
Thus,the program has been executed successfully.

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
def dictionairy(): 
# Declaring hash function      
key_value ={}    
# Initializing the value 
key_value[2] = 56       
key_value[1] = 2 
key_value[5] = 12 
key_value[4] = 24 
key_value[6] = 18      
key_value[3] = 323 
print ("Keys and Values sorted", 
"in alphabetical order by the value") 
# Note that it will sort in lexicographical order 
# For mathematical way, change it to float 
print(sorted(key_value.items(), key = 
lambda kv:(kv[1], kv[0])))

```

## Sample Output

![447278720-b392c533-1d4f-4317-9f57-20c938973cad](https://github.com/user-attachments/assets/a4a7e412-206d-44bc-9305-910284fb517a)

## Result
Thus,the program has been executed successfully.


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
msg=[5, 10, 20]
try:
    print(msg[5])
except IndexError:
    print("You're out of list range")
```
## Output

![447278775-64b30a33-505f-478e-bbd3-52abebb478ac](https://github.com/user-attachments/assets/056f9ab5-1889-4950-b9a7-10efbd221c23)

## Result

Thus,the program has been executed successfully.

# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```

## Output
![447278810-41d81ae2-8c98-4593-96fc-37fb26047070](https://github.com/user-attachments/assets/23a4e4b9-20dd-49d2-baf0-7428e9c4a80b)


## Result
Thus,the program has been executed successfully.
