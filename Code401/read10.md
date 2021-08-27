# Stacks and Queues

## Stack

A LIFO data structure the element which is placed last, is accessed first

![stack](stack1.png)

### Basic Operations

Stack operations may involve initializing the stack, using it and then de-initializing it. Apart from these basic stuffs, a stack is used for the following two primary operations −

- **push()** − storing an element on the stack.

- **pop()** − accessing an element from the stack.

- **peek()** − get the top data element of the stack, without removing it.

- **isFull()** − check if stack is full.

- **isEmpty()** − check if stack is empty.

At all times, we maintain a pointer to the last PUSHed data on the stack. As this pointer always represents the top of the stack, hence named top. The top pointer provides top value of the stack without actually removing it.

## Queue

A FIFO data structure the element which is place first, is accessed first

![queue](Queue.png)

### Basic Operations

- **enqueue()** − adding an element to the queue.

- **dequeue()** − accessing an element from the queue.

- **peek()** − get the first data element of the queue, without removing it.

- **isEmpty()** − check if the queue is empty.
