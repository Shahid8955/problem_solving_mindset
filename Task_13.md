# **Task 13**
# **Modules and Importing**
- Module ek Python file hoti hai, jisme functions, variables, aur classes defined hoti hain. Jab humko kisi specific task ke liye code chahiye hota hai, to hum module ka use karte hain.
## Example
```python
import math
print(math.sqrt(16))
```
### Modules ka use karne ke main reasons
- To reuse the code,
- To avoide the hardcoding,
- For using built in function and
- For hiding our code
```python
import math
print(math.sqrt(16))
print(math.pi)
print(math.log(10))
```
### Date and Time 
```python
import datetime
current_datetime = datetime.datetime.now()
print(current_datetime)
today_date = datetime.date.today()
print(today_date)
birthday_datetime = datetime.datetime(2004,10,11,9,45,30)
print(birthday_datetime)
```