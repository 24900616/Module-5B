# NumPy Program: Column-wise Sorting of a 2D Array

Name: Swetha K

Register No: 212224230284

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
arr=np.array(eval(input()))
print("Given array")
print(arr)
print()
print(np.sort(arr,axis=0))
```

## Output
![image](https://github.com/user-attachments/assets/09f96c6f-49a1-47d9-8326-acf85e82e521)

## Result
Thus the program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.


