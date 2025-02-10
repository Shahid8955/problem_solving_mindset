# **Task 11**
# **Functions – Parameters**
-  function me parameters ka use karke ,  aap code ko reusable bana sakte ho aur hardcoding se bach sakte ho.
```python
# Example
def greet(name):
    print("Hello, " + name + "!")  # Ab parameter ke through koi bhi naam de sakte ho

greet("Shahid")  # Output: Hello, Shahid!
greet("Samad")  # Output: Hello, Samad!
```
```python
# Function with Return Values
def multiply(x, y):
    return x * y

product = multiply(4, 5)  # 4 aur 5 ka multiplication
print(product)  # Output: 20
```
# Local Variable
- Local variable function ke andar define hota hai.
- Function ke bahar accessible nahi hota.
```python
# Example
def greet():
    massage = "Hello, Local variable" #local variable
    print(message)

 greet()
 print(message)   # Error! 'message' is not defined outside the function
 ```
 # Global Variable
- Global variable program ke kisi bhi function ke andar aur bahar accessible hota hai.
- Agar function ke andar global variable ko modify karna ho, toh global keyword ka use karna padta hai.
```python
global_variable = "Hello, Global variable"

def greet():
    print(global_variable)

greet()
print(global_variable)
```
##  Modifying Global Variable
```python
# Example
global_variable = "Hello, Shahid"
def modify():
    global global_variable
    global_variable = "Welcome, Shahid"
modify()
print(global_variable)  
```     
