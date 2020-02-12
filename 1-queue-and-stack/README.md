# Queue & Stack 

## Introduction

    - Two different processing orders
        1) First-in-First-out
        2) Last-in-First-out

    - By completing this card, you should be able to understand
        1) Understand the principle of the processing orders of FIFO and LIFO
        2) Implement these two data structures;
        3) Be familiar with the built-in queue and stack structure;
        4) Solve basic queue-related problems, especial BFS;
        5) Solve basic stacked-related problems;
        6) Understand how system stack helps you when you solve problems using DFS and other recursion algorithms

## Queue: First-in-first-out Data Structure

    - The Goal of this section is to help us:
        1) Understand the definition of FIFO and queue;
        2) Be able to implement a queue by yourself;
        3) Be familiar with the built-in queue structure;
        4) Use queue to solve simple problems.

### First-in-first-out Data Structure

    - In a FIFO data structure, the first element added to the queue will be processed first
    - The insert operation is allso called enqueue.
    - The new element is always added at the end of the queue.
    - The delete operation is called dequeue.
    - You are only allowed to remove the first element. 


### Queue - Implementation

    - To implement a queue, we may use a dynamic array and an index pointing to the head of the queue
    - Enqueue appends a new element to the queue
    - Dequeue removes the first element.

### Circular Queue

    - Use a fixed-sized array and two pointers to indicate the starting position and the ending position.
    - The goal is to reuse the wasted storage.

### Design Circular Queue

    - Design your implementation of the circular queue.
    - The circular queue is a linear data structure which the operations are performed based on FIFO (First in First out) principle and the last position is connected back to the first position to make a circle. It is also called a "Ring Buffer"
    - One of the benefits of the circular queue is that we can make use of the spaces in front of the queue.
    - In normal queue, we cannot insert next element.