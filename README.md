Time Complexity:
================

    Enqueue (Insertion):
    ---------------------
    Adding an element to the end of the queue is a constant-time operation, O(1), regardless of the size of the queue. This is because we simply add the new element to the rear of the queue.

    Dequeue (Deletion):
    -------------------
    Removing an element from the front of the queue is also a constant-time operation, O(1). Regardless of the size of the queue, we only remove the element at the front.

    Front/Rear (Access front/rear element):
    ---------------------------------------
    Accessing the front or rear element of the queue is also a constant-time operation, O(1). We can directly access the front and rear elements without iterating through the entire queue.

Space Complexity:
==================

The space complexity of a queue is O(n), where n is the number of elements in the queue. This is because, in the worst case, the queue will occupy space proportional to the number of elements it holds. Each element in the queue occupies space, and the space used grows linearly with the number of elements.

In summary:
-----------

    Enqueue, Dequeue, and accessing the front/rear element in a queue all have a time complexity of O(1).
    The space complexity of a queue is O(n), where n is the number of elements in the queue.

    Time Complexity:
    ----------------

    Enqueue (Insertion): Think of adding something to the end of a line. When you add something to a queue, it's like adding it to the end of the line. It doesn't matter how long the line is; it takes the same amount of time to add something to the end.

    Dequeue (Deletion): Now, imagine you're removing the first person from the line. No matter how long the line is, it takes the same amount of time to remove the first person.

    Front/Rear (Access front/rear element): When you want to see who is at the front or the end of the line, you can do it instantly. It doesn't matter how many people are in the line; you can quickly check who's at the front or end.

Space Complexity:
-----------------

The amount of space a queue uses grows as you add more things to it. If you add one thing, it takes up a little space. If you add ten things, it takes up more space. So, the space the queue uses increases as you add more items.

In summary:

    Adding, removing, and checking who's at the front or end of a queue is very quick, no matter how many items are in the queue.
    However, the space the queue uses grows as you add more items to it. If you add a lot of items, the queue will use more space.
