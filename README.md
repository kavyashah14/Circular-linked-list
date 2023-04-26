# Circular-linked-list
The circular linked list is a linked list where all nodes are connected to form a circle. In a circular linked list, the first node and the last node are connected to each other which forms a circle. There is no NULL at the end.

![image](https://user-images.githubusercontent.com/70435939/234472072-e229f420-4f1c-4c81-80d8-b5903fe697a4.png)

# Node representation of a Circular Linked List:

struct Node {

    int data;
    
    struct Node *next;
    
};
