#  Queue using Linked List: Display Front and Rear Elements of a Queue

##  Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

##  Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
```python
queue = []

queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')

print('Initial Queue: ' + str(queue))

front = queue[0]
rear = queue[-1]

print("\nElement at the front of the queue is .... ", front)
print("\nElement at the rear of the queue is .... ", rear)
```

## Output

![image](https://github.com/user-attachments/assets/649a54e9-1b03-4cf9-873d-9c3ca34e290b)

## Result
Thus, the program has been executed successfully.
