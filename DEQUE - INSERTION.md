# Exp.No:39  
## DEQUE - INSERTION

---

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

---

### PROGRAM  

```python
from collections import deque
n1=int(input())
n2=int(input())
n3=int(input())
q=deque([])
q.append(n1)
q.append(n2)
q.append(n3)
q.append(14)
q.append(15)

print("The deque after appending at right is :")
print(q)

```

### OUTPUT

<img width="934" height="297" alt="image" src="https://github.com/user-attachments/assets/21185238-66a3-449d-b71f-4890eace46a9" />

### RESULT
Thus the Python program to insert elements at REAR END of deque using a collection built-in function is implemented and executed successfully.
