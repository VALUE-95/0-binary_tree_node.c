```markdown
# Binary Trees Project README

## Table of Contents
1. [Description](#description)
2. [Requirements](#requirements)
3. [Data Structures](#data-structures)
4. [Print Function](#print-function)
5. [Learning Objectives](#learning-objectives)
6. [Resources](#resources)
7. [Usage](#usage)
8. [Contributors](#contributors)
9. [License](#license)

## Description
This is a group project focusing on binary trees in C programming language. The project encompasses various tasks related to understanding and implementing binary trees, including concepts such as binary search trees, traversal methods, tree properties (depth, height, size), and tree types (complete, full, perfect, balanced).

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All files compiled on Ubuntu 20.04 LTS using gcc with specific options
- Code style should adhere to the Betty style guidelines
- No global variables allowed
- Maximum of 5 functions per file
- Usage of standard library is allowed
- README.md file is mandatory
- Header file named `binary_trees.h` with include guards
- Prototypes of all functions should be included in `binary_trees.h`
- All header files should be include guarded

### Allowed Functions
- Functions should not exceed 5 per file
- Prototypes should be included in `binary_trees.h`

## Data Structures
- **Basic Binary Tree:**
  ```c
  struct binary_tree_s
  {
      int n;
      struct binary_tree_s *parent;
      struct binary_tree_s *left;
      struct binary_tree_s *right;
  };
  typedef struct binary_tree_s binary_tree_t;
  ```

- **Binary Search Tree:**
  ```c
  typedef struct binary_tree_s bst_t;
  ```

- **AVL Tree:**
  ```c
  typedef struct binary_tree_s avl_t;
  ```

- **Max Binary Heap:**
  ```c
  typedef struct binary_tree_s heap_t;
  ```

## Print Function
A provided print function is available for visualization purposes. It's not necessary to include it in the repository.

## Learning Objectives
- Understanding what a binary tree is
- Differentiating between a binary tree and a Binary Search Tree
- Recognizing time complexity gain compared to linked lists
- Understanding the concepts of depth, height, and size of a binary tree
- Familiarity with different traversal methods
- Understanding complete, full, perfect, and balanced binary trees

## Resources
Students are encouraged to read or watch materials related to binary trees and data structures for better understanding.

## Usage
Students can use the provided information, resources, and guidelines to complete the project tasks. Testing can be done using appropriate main.c files.

## Contributors
- Tarek Hamdoudi
- Victor Ochuba

## License
This project is licensed under the MIT License - see the LICENSE file for details.
```

You can modify or expand this README file according to your project's specific needs.
