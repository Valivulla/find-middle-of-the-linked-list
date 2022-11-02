# Find Middle of a Linked List

## Problem Statement

Given a linked list, find the middle of the linked list. For example, if the given linked list is 1->2->3->4->5 then the output should be 3. If there are even nodes, then there would be two middle nodes, we need to print the second middle element. For example, if given linked list is 1->2->3->4->5->6 then the output should be 4.

## DEMO

#### 

## SCREENSHOTS



## Algorithm

1. Initialize two pointers, `fast` and `slow`, to the head of the linked list.
2. Move `fast` two nodes and `slow` one node at a time.
3. When `fast` reaches the end of the linked list, `slow` will be at the middle of the linked list.