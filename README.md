# CISC2200 BSTMap Lab (none-template version)

In this lab assignment, we practice implementing two member functions for **Binary Search Tree**. This version does not use **class template**.  
The key type is fixed to **string**, and the value type is fixed to **int**.

## Download starter code

From your terminal (mac or WSL/Ubunto) window, you can use the following command to download it:
```
git clone https://github.com/CISC2200-Spring2026/lab6_nonetemplate.git
```
Alternatively, you can use the following command to download the starter code as a zip file:
```
wget https://github.com/CISC2200-Spring2026/lab6_nonetemplate/archive/refs/heads/main.zip
```

and then unzip it (if it's not automatically unzipped): 
```
unzip main.zip
```

## Requirements:

Please implement the following member functions in the **BSTMap.h**. 

1.  Implement **get** member function that performs a look up with a key, and it shall return the value.
2.  Implement **remove** member function that removes the node with the given key. You can assume the key exists in the BST.
3.  Test your functions by adding more testcases in  **main.cpp**.
4.  The following are some optional practice questions that you can work on:
    - implement **size** member function to return the total number of nodes in the BST.
    - implement a constructor that takes in an array of Keys and an array of Values, and build a optimal BST.
    - implement a **print** member function to display the nodes in the BST in the ascending order.
    - implement a **checkSearchProperty** member function to check if the calling object (a binary tree) satisfies the binary search property: for any node in the tree, the keys stored in its left subtree are less than the node, and the keys stored in its right subtree are greater than the node.
    
   
## Hints

The **main.cpp** provided in this repository tests **remove** and **get** member functions. 
Follow the example to write some more testcases as needed to make sure your functions work for different inputs.

## Submission 

Submit your **BSTMap.h** file to BB by April 22nd, midnight. 
