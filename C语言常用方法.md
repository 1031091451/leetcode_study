# 1.hash表的数据设计

```c
typedef struct Elem{
    int key;
    int Inedx;
    int count;
}Elem;

typedef struct Node{
    Elem* data;
    struct Node* next;
}Node;

typedef struct hashTable{
    Node* head;
    int hashsize;
}hashTable;
```

