# Project Title: BINARY TREES.

## Header File

Make sure to include the binary_trees.h header file in your project, which should contain the prototype for the Binary tree node function.

## Task 0 New node

Creating a new node:

start by calling the binary tree node function, passing the parent node and value that are needed to assigned to the new node.

For example:

binary_tree_t *createnewNode = binary_tree_node(parent, 42); 

This code create a new  node   with  the value of 42 and attachws it to a parent node.

Handling Failure:

• It's essential if your Your function must return a pointer to the new node, or NULL on failure

Working with the new  node  


Once you have a pointer to the newly created node, you can manipulate the binary tree by attaching it to other nodes as left or right children or using it in various binary tree e alogrithm

• However,  for this particular task, the created node does not have any child..


# Task 1

Insertinng a left child node in a Binaryy   tree   - C The 'binary_tree_insert_left`, designed to insert a new node as the left child of an existing node within a binary tree. This will manipulate the binary tree data structure and expand it
This is the prototype below
binary_tree_t *binary_tree_insert_left(binary_tree_t *parent, int value); 

Parameters:

- `parent`: A pointer to the node to insert the left-child in
- `value`: The value to store in the new left child node.

Return Value:
- The function returns a pointer to the newly created node.
- In case of failure or if `parent` is `NULL`, it returns `NULL`. 

How to Use `binary_tree_insert_left` 

1. Include the Header File 

2. Insert the New Left Child**
3. Replacing Existing Left Child
4. Check both syntax and compilation error 

**NOTE:** If the `parent` node already has a left child, the new node will take its place, and the old left child will become the left child of the new node.

## Task 2
Inserting a Right Child Node in a Binary Tree - C Function 

The `binary_tree_insert_right`, designed to insert a new node as the right child of an existing node within a binary tree. This will expand the binary tree's right data structure and also manipulate it.  Below, you'll find a concise description of how to use this function effectively.

binary_tree_t *binary_tree_insert_right(binary_tree_t *parent, int value);
```
Parameters:
- `parent`: A pointer to the node where the new right child will be inserted.
- `value`: The value to store in the new right child node. 

Return Value:
• - Your function must return a pointer to the created node, or NULL on failure or if parent is NULL 

• If parent already has a right-child, the new node must take its place, and the old right-child must be set as the right-child of the new node.

How to Use `binary_tree_insert_right` 

1. Including the Header File 

2. Inserting a New Right Child 

3. Handling Failure 

4. Replacing Existing Right Child

## Task 3 

Deleting an Entire Binary Tree - C Function 

The binary_tree_delete`, designed to delete an entire binary tree efficiently. The function accepts a pointer to the root node of the tree to be deleted and recursively deallocates all memory associated with the tree nodes. Below, you'll find a concise description of how to use this function effectively. 

void binary_tree_delete(binary_tree_t *tree);

Parameter:
- `tree`: A pointer to the root node of the binary tree to delete. 

How to Use `binary_tree_delete` 

1. Including the Header File 

2. Deleting the Binary Tree 

3. Handling NULL Trees 

The function automatically checks if `tree` is `NULL` and takes no action if `tree` is already empty.


## Task 4
Checking if a Node is a Leaf in a Binary Tree - C 

The binary_tree_is_leaf`, which verifies whether a given node in a binary tree is a leaf node. A leaf node is a node that has no left or right children. The function accepts a pointer to the node to check and returns `1` if the node is a leaf and `0` otherwise. If the input node is `NULL`, the function also returns `0`. Below, you'll find a concise description of how to use this function effectively.


int binary_tree_is_leaf(const binary_tree_t *node);


Parameter:
- `node`: A pointer to the node you want to check if it's a leaf. 

How to Use `binary_tree_is_leaf` 

1. Including the Header File 

2. Checking if a Node is a Leaf
3. Handling NULL Nodes


