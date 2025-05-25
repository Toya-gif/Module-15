# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

## ALGORITHM:

1. *Start the program.*
2. Import the required modules (build and Node from binarytree).
3. Define a list x representing the expression tree in pre-order fashion (with None for missing nodes).
4. Use the build() function to generate the binary tree.
5. Print the *inorder* and *postorder* traversal of the tree.
6. *End the program.*

## PROGRAM:
from binarytree import build

nodes=['*',4,'-',5,'+',2,7]

root=build(nodes)

print(root.inorder)

print(root.postorder)

## OUTPUT
![image](https://github.com/user-attachments/assets/b64a2fc2-3256-47a0-8dd5-e7aa1ab83129)![image](https://github.com/user-attachments/assets/4c9f0d95-eb92-4183-a02e-449221c9dd78)

## RESULT
Thus, a Python program to build the given expression tree and print the inorder and postorder traversals was implemented successfully.
