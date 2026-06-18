# Data Structures Implementation in C++

## Objective

The objective of this project is to implement core data structures from scratch in C++ without using STL containers. The project demonstrates insertion, deletion, and search operations for Stack and Queue along with sample outputs and time complexity analysis.

## Data Structures Implemented

1. Stack
2. Queue

## Features

### Stack

* Insert (Push)
* Delete (Pop)
* Search
* Display Elements

### Queue

* Insert (Enqueue)
* Delete (Dequeue)
* Search
* Display Elements

## Technologies Used

* C++
* Visual Studio Code
* GCC/G++ Compiler

## File Structure

```text
DataStructures/
│
├── Stack.cpp
├── Queue.cpp
└── README.md
```

## How to Compile and Run

### Stack

```bash
g++ Stack.cpp -o Stack
./Stack
```

### Queue

```bash
g++ Queue.cpp -o Queue
./Queue
```

## Sample Output

### Stack

```text
10 inserted into stack.
20 inserted into stack.
30 inserted into stack.
Stack elements: 30 20 10
20 found in stack.
30 deleted from stack.
Stack elements: 20 10
```

### Queue

```text
10 inserted into queue.
20 inserted into queue.
30 inserted into queue.
Queue elements: 10 20 30
20 found in queue.
10 deleted from queue.
Queue elements: 20 30
```

## Time Complexity Analysis

### Stack

| Operation     | Complexity |
| ------------- | ---------- |
| Insert (Push) | O(1)       |
| Delete (Pop)  | O(1)       |
| Search        | O(n)       |

### Queue

| Operation        | Complexity |
| ---------------- | ---------- |
| Insert (Enqueue) | O(1)       |
| Delete (Dequeue) | O(1)       |
| Search           | O(n)       |

## Driver Program

The `main()` function in each source file acts as a driver program to demonstrate the functionality of the data structure. It performs insertion, deletion, search, and display operations.

## Conclusion

This project successfully implements Stack and Queue data structures from scratch in C++. The operations were manually implemented without using STL containers, demonstrating a clear understanding of fundamental data structure concepts and their time complexities.

