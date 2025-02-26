# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Arrays, Linked Lists and Doubly Linked Lists all allow programmers to organize data in a sequence. So, how would you choose to use one over the other?

In your response, make sure to compare the time complexities for insertion, removal, and random access (grabbing a particular known element by index/position) for each data structure as well as memory usage and ease of traversal.

### Response 1

XAVIER

> When it comes to choosing between the various data structures, it all truly depends on the purpose of the operation. Different data structures all have their own benefits such as their insertion and removal time complexity. 

### specialties
    Arrays: Useful when memory efficency is needed alongside fast random access.

    Doubly linked lists: Useful when traversing in both directions is needed alongside time efficient insertions and deletions throughout both ends of the list.

    Linked lists: Useful when youre frequently inserting and deleting elements throughout the head and the tail.

Overall, the usage varies based on the time complexity for the use case of whatever it may be that you're working on. You could prioritize a linked list if you want a quick form of insertion and deletion from both ends. However, if you want to have a quick form of random access and minimal ram usage, then an array would be the best choice. 

## Prompt 2

Imagine you are developing a web browser's "back" button functionality. When a user clicks "back," the browser should navigate to the previously visited webpage.

Would you use a stack or a queue to implement this functionality?

In your response, explain what a Stack/Queue is and why it would be best for this use case. Make sure that your response includes the terms LIFO or FIFO.

### Response 2

XAVIER

To implement a web browser’s "back" button functionality, a stack is the best choice because it follows the LIFO principle. A stack allows the browser to store visited pages in order, meaning that when the user clicks back, the most recently visited page is removed and the browser navigates to the previous one. For example, if a user visits pages A, B, and C in sequence, each page is pushed onto the stack. Clicking "back" pops C from the stack, returning to B; clicking "back" again removes B, taking the user back to A. This behavior aligns perfectly with LIFO, making a stack the ideal structure for this functionality. A queue, on the other hand, follows FIFO, meaning the oldest page would be removed first, which is not how a "back" button should function. Since users expect to return to the most recently visited page first, a queue would be unsuitable.

## Prompt 3

What is an Abstract Data Type and why are they worth learning about?

### Response 3

AUTUMN

## Prompt 4

A few classic problems involving a stack are the `isBalanced` and `isPalindrome` functions. Choose one of these functions and provide a solution to it along with a brief lesson explaining how it works.

### Response 4

AUTUMN
