#  Stack using Linked List: Stack Implementation (Top Element Display)

##  Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

##  Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

##  Program
```python
stack = []

stack.append(input("Insert the first element:\n"))
stack.append(input("Insert the second element:\n"))
stack.append(input("Insert the third element:\n"))

print("\nInitial stack:", stack)
print("\nElement at the top of the stack is .... ", stack[-1])
```

## Output

![image](https://github.com/user-attachments/assets/a4756290-0dbc-4d0c-b58b-67f7aa3da2af)

## Result
Thus, the program has been executed successfully.
