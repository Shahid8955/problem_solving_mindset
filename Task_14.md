# **Task 14**
# Error Handling – try, except, finally 
- Error handling ka use kar ke hum apne program ko crash hone se bachate hain aur errors ko properly manage karte hain.
- Error handling se hum program ko control mein rakh sakte hain, jab koi unexpected situation aaye. Python mein try aur except block ka use karke hum errors ko handle karte hain.
## Keyword Use
- **try:**
Yeh block wo code run karta hai jisme error aa sakti hai.
- **except:**
Agar try block mein koi error hoti hai, to except block us error ko handle karta hai. Yahan aap error message ya koi fix action de sakte ho.
- **finally:**
Yeh block hamesha run hota hai, chahe error aaye ya na aaye.
##  Example
```python
try: 
    number = int(input("Enter the number:"))
    
    print("You entered:", number)
except valueerror:
    print("Inviled number") 
```
## Using Multiple except Blocks
```python
try:
    # Taking two inputs from the user
    num1 = int(input("Enter the first number: "))
    num2 = int(input("Enter the second number: "))

    result = num1 / num2
    print("The result is:", result)
    
except ZeroDivisionError:
    print("Error! You can't divide by zero.")
    
except ValueError:
    print("Invalid input! Please enter valid numbers.")
```
## Using finally Block
- **Finally** block hamesha run hota hai, chahe error aaye ya na aaye.
```python
try:
    print("Connecting to database...")

    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Closing the database connection.")
```