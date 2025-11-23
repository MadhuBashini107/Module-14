# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```python
from collections import deque
a=input()
b=input()
c=input()
q=deque([])
q.append(a)
q.append(b)
q.append(c)
q.popleft()
print("The deque after deletion is :")
print(q)
```

### OUTPUT

<img width="932" height="294" alt="image" src="https://github.com/user-attachments/assets/74e0e0df-0267-41a0-be12-4393f4047d98" />

### RESULT
Thus Python program to delete elements at FRONT END of deque using a collection built-in function is implemented and executed successfully.
