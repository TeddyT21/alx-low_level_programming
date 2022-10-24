# C - More singly linked lists

In this project, I continued to practice building and using singly linked lists in C.

* lists.h: Header file containing definitions and prototypes for all types and functions written for the project.

| Type/File                | Definition/Prototype                                                           |
| ------------------------ | ------------------------------------------------------------------------------ |
| struct listint_s         | <ul><li>int n</li><li>struct listint_s *next</li></ul>                     |
| typedef listint_t        | struct listint_s                                                               |
| 0-print_listint.c        | size_t print_listint(const listint_t *h);                                      |
| 1-listint_len.c          | size_t listint_len(const listint_t *h);                                        |
| 2-add_nodeint.c          | listint_t *add_nodeint(listint_t **head, const int n);                         |
| 3-add_nodeint_end.c      | listint_t *add_nodeint_end(listint_t **head, const int n);                     |
| 4-free_listint.c         | void free_listint(listint_t *head);                                            |
| 5-free_listint2.c        | void free_listint2(listint_t **head);                                          |
| 6-pop_listint.c          | int pop_listint(listint_t **head);                                             |
| 7-get_nodeint.c          | listint_t *get_nodeint_at_index(listint_t *head, unsigned int index);          |
| 8-sum_listint.c          | int sum_listint(listint_t *head);                                              |
| 9-insert_nodeint.c       | listint_t *insert_nodeint_at_index(listint_t **head, unsigned int idx, int n); |
| 10-delete_nodeint.c      | int delete_nodeint_at_index(listint_t **head, unsigned int index);             |
| 100-reverse_listint.c    | listint_t *reverse_listint(listint_t **head);                                  |
| 101-print_listint_safe.c | size_t print_listint_safe(const listint_t *head);                              |
| 102-free_listint_safe.c  | size_t free_listint_safe(listint_t **h);                                       |
| 103-find_loop.c          | listint_t *find_listint_loop(listint_t *head);                                 |

## Tasks :page_with_curl:

Q0. Print list : C function that prints all the elements of a listint_t linked list.

Q1. List length : C function that returns the number of elements in a listint_t linked list.

Q2. Add node: C function that adds a new node at the beginning of a listint_t linked list.

Q3. Add node at the end: C function that adds a new node at the end of a listint_t linked list.

Q4. Free list: C function that frees a listint_t linked list.

Q5. Free: C function that frees a listint_t linked list.

Q6. Pop: C function that deletes the head node of a listint_t linked list.

Q7. Get node at index: C function that locates a given node of a listint_t linked list.

Q8. Sum list: C function that returns the sum of all the data (n) of a listint_t linked list.

Q9. Insert: C function that inserts a new node to a listint_t linked list at a given position.

Q10. Delete at index : C function that deletes the node at a given index of a listint_t linked list.

Q11. Reverse list: C function that reverses a listint_t linked list using a maximum of one loop and two variables.

Q12. Print (safe version): C function that prints a listint_t linked list safely (ie. can free lists containing loops).

Q13. Free (safe version): C function that frees a listint_t linked list safely (ie. can free lists containing loops).

Q14. Find the loop: C function that finds the loop contained in a listint_t linked list using a maximum of two variables.
