# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
```
def create(r, c):
    print("Enter matrix row by row:")
    return [[int(input(f"Element [{i+1}][{j+1}]: ")) for j in range(c)] for i in range(r)]

r = int(input("Enter number of rows: "))
c = int(input("Enter number of columns: "))

matrix = create(r, c)

transpose = [[matrix[j][i] for j in range(r)] for i in range(c)]

print("Transposed Matrix:")
for row in transpose:
    print(row)

```

## OUTPUT:
![447321986-03abde04-c8c7-4754-b539-e17006aeaec1](https://github.com/user-attachments/assets/9a1171b8-2fdd-4c61-89ad-f515c12b2f6f)

## RESULT:
Thus, the program is executed successfully

