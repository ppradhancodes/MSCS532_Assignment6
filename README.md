# Medians and Order Statistics & Elementary Data Structures Implementation and Analysis

This project implements and analyzes basic data structures including arrays, matrices, stacks, queues, and linked lists in Python.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Implemented Data Structures](#implemented-data-structures)
4. [Performance Analysis](#performance-analysis)
5. [Summary of Findings](#summary-of-findings)

## Installation

This project requires Python 3.6 or later. No additional libraries are needed.

To get started, clone this repository:

## Usage

To run the implementations and tests, execute the main Python script:

This will run through all the implemented data structures, perform basic operations, and output the results.

## Implemented Data Structures

1. Matrix (2D Array)
2. Stack
3. Queue
4. Linked List

Each data structure is implemented in its own class with basic operations.

## Performance Analysis

The time complexity for basic operations of each data structure is as follows:

### Matrix (2D Array)
- Access: O(1)
- Insertion/Deletion at end: O(1) amortized
- Insertion/Deletion at arbitrary position: O(n)

### Stack
- Push: O(1)
- Pop: O(1)
- Peek: O(1)

### Queue
- Enqueue: O(1)
- Dequeue: O(n) for array implementation, O(1) for optimized implementations
- Front: O(1)

### Linked List
- Insertion at beginning: O(1)
- Insertion at end: O(n)
- Deletion: O(n)
- Search: O(n)

## Summary of Findings

1. Arrays and Matrices:
   - Provide fast random access (O(1))
   - Efficient for scenarios requiring direct indexing
   - Useful in image processing, scientific computing, and game development

2. Stacks:
   - Offer constant time operations for all basic functions
   - Ideal for LIFO (Last-In-First-Out) scenarios
   - Commonly used in function call management, undo mechanisms, and expression parsing

3. Queues:
   - Efficient for FIFO (First-In-First-Out) operations
   - Array implementation may have O(n) dequeue, which can be optimized
   - Essential in task scheduling, breadth-first search, and data buffering

4. Linked Lists:
   - Provide dynamic size management
   - Efficient for frequent insertions and deletions, especially at the beginning
   - Useful in implementing hash tables, managing dynamic data sets, and representing polynomial arithmetic

The choice of data structure depends on specific application requirements. Arrays excel in random access and cache efficiency, while linked lists are superior for dynamic size management and frequent insertions/deletions. Stacks and queues, whether implemented with arrays or linked lists, are crucial for managing data with specific access patterns in various algorithms and systems.

Understanding these fundamental data structures and their trade-offs is essential for efficient algorithm design and software development.