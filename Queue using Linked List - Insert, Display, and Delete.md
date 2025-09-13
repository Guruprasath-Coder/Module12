# 🌀 Queue using Linked List - Insert, Display, and Delete

## 🎯 Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.

---

## 🧠 Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program
```python
# Queue Implementation using List

# Step 1: Create an empty queue
queue = []

# Step 2: Insert elements into the queue
queue.append('a')
queue.append('b')
queue.append('c')

# Step 3: Display initial queue
print("Queue after elements are inserted:", queue)

# Step 4: Delete first element (FIFO)
removed_element = queue.pop(0)
print("Deleting the first element inserted:", removed_element)

# Step 5: Display updated queue
print("Queue after the first element is deleted:", queue)


## Output
Queue after elements are inserted: ['a', 'b', 'c']
Deleting the first element inserted: a
Queue after the first element is deleted: ['b', 'c']

## Result

The Python program successfully demonstrated Queue operations using a list in Python:

Inserted elements into the queue.

Displayed all inserted elements.

Deleted the first element following FIFO (First In First Out) order.

Displayed the updated queue after deletion
