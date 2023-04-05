0. This function prints all the elements of a listint_t list.

1. This function returns the number of elements in a linked listint_t list.
2. This function adds a new node at the beginning of a listint_t list.

3. Write a function that adds a new node at the end of a listint_t list.
    Prototype: listint_t *add_nodeint_end(listint_t **head, const int n);
    Return: the address of the new element, or NULL if it failed
4. This function frees a listint_t list.
    Prototype: void free_listint2(listint_t **head);
    The function sets the head to NULL

5. This function deletes the head node of a listint_t linked list, and returns the head node’s data (n).
    Prototype: int pop_listint(listint_t **head);
   it returns 0 if the linked list is empty

6. This function returns the nth node of a listint_t linked list.
    Prototype: listint_t *get_nodeint_at_index(listint_t *head, unsigned int index);
    where index is the index of the node, starting at 0
    if the node does not exist, return NULL

7. This function returns the sum of all the data (n) of a listint_t linked list
    Prototype: listint_t *get_nodeint_at_index(listint_t *head, unsigned int index)
    where index is the index of the node, starting at 0
   if the node does not exist, return NULL
8. This function returns the sum of all the data (n) of a listint_t linked list.
    Prototype: int sum_listint(listint_t *head);
    if the list is empty, return 0

9. This function inserts a new node at a given position.

    Prototype: listint_t *insert_nodeint_at_index(listint_t **head, unsigned int idx, int n);
    where idx is the index of the list where the new node should be added. Index starts at 0
    Returns: the address of the new node, or NULL if it failed
    if it is not possible to add the new node at index idx, do not add the new node and return NULL
 
10. WThis function  deletes the node at index index of a listint_t linked list.

    Prototype: int delete_nodeint_at_index(listint_t **head, unsigned int index);
    where index is the index of the node that should be deleted. Index starts at 0
    Returns: 1 if it succeeded, -1 if it failed
                                                  
