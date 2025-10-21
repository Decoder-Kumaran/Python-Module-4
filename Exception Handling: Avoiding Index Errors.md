# PYTHON MODULE - 4
# (D) Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim:
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm:
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program:

    lst = [1,4,8,9,10,5]
    try :
        index = int(input("Enter a index : "))
        print("Th Element in the given index is ",lst[index])
    except :
        print("You're out of list range")

## Output:

<img width="1918" height="470" alt="image" src="https://github.com/user-attachments/assets/d5ef97df-59a2-49c1-bcf5-95f96538d847" />
<img width="1918" height="82" alt="image" src="https://github.com/user-attachments/assets/2e7a74cb-d024-45af-827f-e813134af5f7" />


## Result:

Thus, The Python program that handles an **IndexError** when trying to access an element beyond the available range of a list was executed successfully.
