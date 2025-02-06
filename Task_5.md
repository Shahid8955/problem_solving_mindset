# Task 5
# Operators: Arithmetic, Assignment, Comparison, Logical
## 1. **Arithmetic Operators:**
-  Arithmetic Operators ka use Addition, Subtraction, Multiplication, Division kar ne ke liye kiya jata hai
- Arithmetic operators basic mathematical calculations ke liye use hote hain.
- addition = num1 + num2         
- subtraction = num1 - num2      
- multiplication = num1 * num2   
- division = num1 / num2         
- floor_division = num1 // num2 iska use kar ke decimal value ko remove kiya jata hai 
- modulus = num1 % num2          
- exponentiation = num1 ** num2
 ## Best Practices
  ```python
a = 50
b = 10

# Addition
print(a + b)  

# Subtraction
print(a - b)

# Multiplication
print(a * b)  

# Division 
print(a / b)  

# Floor Division 
print(a // b)  

# Modulus 
print(a % b)  

# Exponentiation (power)
print(a ** b) 
```
## 2. Assignment Operators:
- Used to assign values:
## Best Practices
```python
x = 10
x += 5  # x = x + 5 → 15
x *= 2  # x = x * 2 → 30
print(x)
```
 ## 3. **Comparison Operators:**
 -  Comparison Operators: Do values ko compare karna.
 - **Greater Than (`>`):** Checks if one value is greater than another.
  - **Equal To (`==`):** Checks equality.
 - **Not Equal (`!=`):** Checks inequality.
- **Less Than (`<`):** Checks if one value is less than another.
## Best Practices
```python
a = 10
b = 5

# Equal to
print(a == b)   False

# Not equal to
print(a != b)   True

# Greater than
print(a > b)    True

# Less than
print(a < b)    False

# Greater than or equal to
print(a >= b)   True

# Less than or equal to
print(a <= b)   False
```

## 3. **Logical Operators:**
-  Logical Operators ka use Multiple conditions ko combine karne ke liye kiya jata hai
- **`and`:** Both conditions must be true.Example: Student must have score > 50 **and** attendance > 75%.
 - **`or`:** At least one condition must be true.
 - **`not`:** Inverts the Boolean value.
 ## Best Practices
 ```python
score = 75
attendance = 85

if score > 50 and attendance > 75:
    print("Pass with good attendance")  # Output: Pass with good attendance