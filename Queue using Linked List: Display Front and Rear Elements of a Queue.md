# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

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
# Queue using List (simulating Linked List behavior)

# Step 1: Initialize Queue
queue = []

# Step 2: Insert elements
queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')

# Step 3: Display Initial Queue
print("Initial Queue:", queue)

# Step 4: Identify front and rear elements
front = queue[0]
rear = queue[-1]

# Step 5: Print Results
print("Front Element of Queue:", front)
print("Rear Element of Queue:", rear)


## Output

Initial Queue: ['a', 'b', 'c', 'd']
Front Element of Queue: a
Rear Element of Queue: d

## Result

Thus, the Python program to display the front and rear elements of a queue using list implementation was successfully executed.
