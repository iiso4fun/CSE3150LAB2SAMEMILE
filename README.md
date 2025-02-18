# C++ Linked List Project

## Project Description

This program provides an implementation of a singly linked list in C++. It includes operations for creating, displaying, modifying, and deleting nodes. Unit testing is performed using the **Doctest** framework.

## Source Code Files

- **llist.h** - Defines the `Node` structure and function declarations.
- **llist.cpp** - Contains the implementation of linked list operations.
- **llisttest.cpp** - Unit tests written using the **Doctest** framework.
- **doctest.h** - Single-header testing framework included for validation.

## Functionality

- **List Creation** - Construct a linked list from a vector of integers.
- **Displaying the List** - Print the elements in a readable format.
- **Retrieving Elements** - Fetch a value from the list using an index.
- **Node Removal** - Delete a node at a specified index.
- **Clearing the List** - Free allocated memory and reset the list.
- **Automated Testing** - Verify correctness using unit tests.

## How to Compile and Run

### Compiling

Use the following command to compile the project:

```bash
 g++ -o test llisttest.cpp llist.cpp -std=c++17
```

### Running Tests

Execute the compiled file to run the unit tests:

```bash
 ./test
```

##

