# Queue-Remove Two String Values from the Rear End in Python 🧵

This Python program demonstrates how to manage a list of strings and remove the last two elements (i.e., from the rear of the list).
## NAME : Shanmuga Vasanth M
## REG NO: 212223040191
## 🎯 Aim

To write a Python program to:
- Accept `n` string values from the user
- Remove the last two values (rear end of the list)
- Display the updated list

## 🧠 Algorithm

1. Create an empty list `q`.
2. Read an integer `n` from the user (number of strings).
3. Loop `n` times:
   - Read a string input.
   - Append it to the list `q`.
4. Remove the last element using `pop()`.
5. Remove the next last element using `pop()` again.
6. Display the updated list.

##  Program:
~~~c
string_list = []
n = int(input("Enter the number of strings: "))
for i in range(n):
    val = input(f"Enter string {i + 1}: ")
    string_list.append(val)
if len(string_list) >= 2:
    string_list.pop()
    string_list.pop()
elif len(string_list) == 1:
    string_list.pop()
    print("Only one string was in the list, so it's now empty.")
else:
    print("The list is empty. Nothing to remove.")
if string_list:
    print("Updated list after removing last two elements:", string_list)
else:
    print("No elements remaining in the list.")
~~~

### Output:
![442494708-e3b0d5a6-8fcc-4773-b780-b3d248ba565a](https://github.com/user-attachments/assets/dd1faef1-e2ef-4214-9d9b-8a2134d9ba7e)


## Result:
Thus the program has been executed successfully.
