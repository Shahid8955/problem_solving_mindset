# Task 8
# For Loop in Python
# Objective:
- For loop Python me ek iterative statement hai jo kisi sequence (list, tuple, string, ya range) ke elements par iterate karne ke liye use hota hai. Ye loop fixed iterations ke liye useful hota hai.
```python
# Syntax 
for variable in sequence:
    for topic in learning_topics:
        # Code to execute in loop
```
## Example
```python
for number in range(1, 6):  
    print(number)
```
## Explanation 
- range(1, 6) 1 se 5 tak numbers generate karta hai (last number 6 include nahi hota).
- for number in range(1, 6): har number par loop chalayega jo is range me aayega.
- print(number) har number ko ek naye line par print karega. 
## Best Practices
- Agar index values ki zaroorat ho to enumerate() ka use karo.
- Dictionaries me key-value pairs par iterate karne ke liye .items() ka use karo.
- Loop ke dauraan lists ko modify karne se bacho taaki errors na aaye. 