# Queue-Queue Values in Descending Order Using Python 🧮

This Python program simulates a queue using a list, removes the first two elements (FIFO order), and displays the remaining values in descending order.
## NAME : Shanmuga Vasanth M
## REG NO: 212223040191
## 🎯 Aim

To write a Python program to:
- Accept user inputs into a list (queue)
- Remove the first two elements (simulating dequeue)
- Display the remaining values in **descending order**

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` to determine how many elements will be added.
3. Loop `n` times:
   - Read an input value.
   - Append it to the list `q`.
4. Remove the first element using `pop(0)`.
5. Remove the second element using `pop(0)` again.
6. Sort the list in descending order.
7. Print the updated list.

## 🧪 Program: 
~~~c
queue = []
n = int(input("Enter the number of elements in the queue: "))
for i in range(n):
    value = int(input(f"Enter element {i + 1}: "))
    queue.append(value)
if len(queue) >= 2:
    queue.pop(0)
    queue.pop(0)
elif len(queue) == 1:
    queue.pop(0)
    print("Only one element was in the queue, so it's now empty.")
else:
    print("The queue is empty. Nothing to remove.")
if queue:
    queue.sort(reverse=True)
    print("Remaining elements in descending order:", queue)
else:
    print("No elements remaining in the queue.")
~~~

### Output:
![442494492-7f245c84-d125-4356-a0e0-7c1301bde878](https://github.com/user-attachments/assets/87712230-fd9a-424e-a5d1-15093227e7ab)


## Result:
Thus the program has been executed successfully.
