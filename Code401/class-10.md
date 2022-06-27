# Read: 10 - Stacks and Queues

## Reading

Read and save for reference: [Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)

Stack

* A **stack** is a data structure that consists of Nodes. Each Node references the next Node in the stack, but does not reference its previous.
* Common terminology for a stack:
  * **Push** - Nodes or items that are put into the stack are pushed
  * **Pop** - Nodes or items that are removed from the stack are popped. When you attempt to pop an empty stack an exception will be raised.
  * **Top** - This is the top of the stack.
  * **Peek** - When you peek you will view the value of the top Node in the stack. When you attempt to peek an empty stack an exception will be raised.
  * **IsEmpty** - returns true when stack is empty otherwise returns false.
* **FILO** - First In Last Out
* **LIFO** - Last In First Out
* Pushing a Node onto a stack will always be an O(1) operation. This is because it takes the same amount of time no matter how many Nodes (n) you have in the stack.
* When adding a Node, you push it into the stack by assigning it as the new top, with its next property equal to the original top.
* Popping a Node off a stack is the action of removing a Node from the top. When conducting a pop, the top Node will be re-assigned to the Node that lives below and the top Node is returned to the user.
* When conducting a peek, you will only be inspecting the top Node of the stack. Typically, you would check isEmpty before conducting a peek. This will ensure that an exception is not raised. Alternately, you can wrap the call in a try/catch block.

[Stack Visualization](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/stack1.PNG)

Queue

* Common terminology for a queue is
  * **Enqueue** - Nodes or items that are added to the queue.
  * **Dequeue** - Nodes or items that are removed from the queue. If called when the queue is empty an exception will be raised.
  * **Front** - This is the front/first Node of the queue.
  * **Rear** - This is the rear/last Node of the queue.
  * **Peek** - When you peek you will view the value of the front Node in the queue. If called when the queue is empty an exception will be raised.
  * **IsEmpty** - returns true when queue is empty otherwise returns false.
* When you add an item to a queue, you use the enqueue action. This is done with an O(1) operation in time because it does not matter how many other items live in the queue (n); it takes the same amount of time to perform the operation.
* When you remove an item from a queue, you use the dequeue action. This is done with an O(1) operation in time because it doesn’t matter how many other items are in the queue, you are always just removing the front Node of the queue. Typically, you would check isEmpty before conducting a dequeue. This will ensure that an exception is not raised. Alternately, you can wrap the call in a try/catch block.

[Queue Visualization](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/images/Queue.PNG)
