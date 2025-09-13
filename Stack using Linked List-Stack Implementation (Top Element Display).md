# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

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

## 💻 Program
```python
# Step 1: Initialize an empty stack
stack = []

# Step 2: Insert 3 elements from the user
for i in range(3):
    value = input("Enter element " + str(i+1) + ": ")
    stack.append(value)

# Step 3: Display the stack
print("\nStack after inserting elements:", stack)

# Step 4: Display the top element
top_element = stack[-1]
print("Top element of the stack is:", top_element)

## Output

Enter element 1: 10
Enter element 2: 20
Enter element 3: 30

Stack after inserting elements: ['10', '20', '30']
Top element of the stack is: 30

## Result

Thus, the Python program to implement a stack and display the top element was successfully executed.
