# Find Middle of a Linked List

## Problem Statement

Given a linked list, find the middle of the linked list. For example, if the given linked list is 1->2->3->4->5 then the output should be 3. If there are even nodes, then there would be two middle nodes, we need to print the second middle element. For example, if given linked list is 1->2->3->4->5->6 then the output should be 4.

## DEMO

#### https://valivulla.github.io/find-middle-of-the-linked-list/

## SCREENSHOTS

![image](https://user-images.githubusercontent.com/91062991/199556729-9f3517fc-56b0-4fa5-aa53-50491ae0f214.png)

![image](https://user-images.githubusercontent.com/91062991/199556807-bf9352ae-8add-456d-af92-6df74dd0ac89.png)

![image](https://user-images.githubusercontent.com/91062991/199557190-e6d6684a-82f3-4e7c-bea7-837ebe5a12b9.png)

### If value is 1 then

find-middle-of-the-linked-list

### If there are 2 middle nodes then

![image](https://user-images.githubusercontent.com/91062991/199557825-d95ba986-6dda-4a90-88b7-062bef855363.png)

## Algorithm

1. Initialize two pointers, `fast` and `slow`, to the head of the linked list.
2. Move `fast` two nodes and `slow` one node at a time.
3. When `fast` reaches the end of the linked list, `slow` will be at the middle of the linked list.
