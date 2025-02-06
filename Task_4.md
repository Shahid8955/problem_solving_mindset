# Task 4
## Data Types: Lists, Tuples, Dictionaries (aur Sets)
## List
- **Ordered Collection:** List mein elements ka ek fixed order hota hai.
- **Mutable:** List ke elements ko change, add, ya remove kiya ja sakta hai.
- **Memory Overhead:** Lists memory ka zyada use kar sakti hain, kyunki woh dynamic hoti hain.
- Example
```python
my_list = ["car", "bike", "watch", "home"]
print(my_list)
```
## Tuples
- **Creation:** project_feedback ek tuple hai jisme har element ek tuple hai (topic aur status).
- **Immutability:** Tuple ke elements change nahi kiye ja sakte, isliye ye safe data storage ke liye best hai jab aapko data ko accidental modification se bachana ho.
```python
# Example
my_tuple = (1, 2, 3, "Python", 4.5)
print(my_tuple[0])  
print(my_tuple[3]) 
```
## Dictionaries
-  **Creation:**`topic_status` dictionary hai jisme keys (learning topics) se associated values (status) store hain.
- **Advantages:** Fast lookup, clear key-value mapping.
```python
# Example
my_dict = {"Name": "Firoz", "Age": 21, "City": "Haryana"}
print(my_dict)
```
## Sets
- **Creation:** unique_topics set hai jismein duplicate values ko automatically remove kiya jata hai.
```python
#Example 
my_set = {1,2,3,4,5}
 print(my_set)
 ```
