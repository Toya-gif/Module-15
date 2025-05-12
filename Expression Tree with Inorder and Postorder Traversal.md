# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
WRITE YOUR CODE
from binarytree import build
s=['*','+','-',9,3,8,4]
t=build(s)
print(t.inorder)
print(t.postorder)
```

## OUTPUT
```
```
![image](https://github.com/user-attachments/assets/50762288-c447-46b0-9ac1-24472b84497a)


## RESULT
Thus the program is done and verified.
