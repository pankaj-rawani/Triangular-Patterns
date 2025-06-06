# Triangular Patterns

This repository contains Python implementations for basic triangular star patterns often used in programming practice and interviews.

## 📌 Patterns Covered

1. **Lower Triangular Pattern**
2. **Upper Triangular Pattern**
3. **Pyramid Pattern**

---

## 🔸 1. Lower Triangular Pattern
```
n = 5
for i in range(1, n + 1):
    print("*" * i)
*
**
***
****
*****
```


## 🔸 2. Lower Triangular Pattern
```
n = 5
for i in range(n, 0, -1):
    print(" " * (n - i) + "*" * i)
*****
 ****
  ***
   **
    *
```


## 🔸 3. Lower Triangular Pattern
```
n = 5
for i in range(1, n + 1):
    print(" " * (n - i) + "*" * (2 * i - 1))

    *
   ***
  *****
 *******
*********
```

