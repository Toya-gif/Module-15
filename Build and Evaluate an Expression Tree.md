# Ex. No: 15A - Debug a Python function to build a Binary tree.
1. Use appropriate Package and build module to build a tree

2. Define def buildtree(L): to build a binary tree

2. Print the Maximum and minimum leaf depths of the binary tree.

## AIM:
To write a Python program to build a binary tree with a Maximum and minimum leaf depths of the binary tree.

## ALGORITHM:

Input Assignment:
Assign the input list L to a variable x.

Tree Construction:
Use build(x) from the binarytree module to construct a binary tree r from the list x.

Display Tree in Level Order:

Print "Binary tree:"

Loop through each value i in r.values (level-order list of node values).

For each value, print it followed by " -->", keeping output on the same line.

Print Maximum Leaf Depth:

Print r.max_leaf_depth, which gives the maximum depth among all leaf nodes.

Print Minimum Leaf Depth:

Print r.min_leaf_depth, which gives the minimum depth among all leaf nodes.


## PYTHON PROGRAM

from binarytree import Node, build

def buildtree(L):

    x=L
    r=build(x)
    print("Binary tree:")
    for i in r.values:
        print(i,"-->",end='')
    print("\nMaximum leaf depth:", r.max_leaf_depth)
    print("\nMinimum leaf depth:", r.min_leaf_depth)
        
## OUTPUT
![image](https://github.com/user-attachments/assets/96da7a20-f9fc-4dd6-b98d-92c087541ef4)![image](https://github.com/user-attachments/assets/835dac31-fc6f-4025-b6bd-402c39d6c0b1)

## RESULT
Thus, a Python program to build a binary tree with a Maximum and minimum leaf depths of the binary tree was implemented successfully.
