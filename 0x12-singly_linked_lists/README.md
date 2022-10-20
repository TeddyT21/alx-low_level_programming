# C - Singly linked lists

In this project, I practiced building and using singly linked lists
in C while learning when and why to use linked lists versus arrays.

## Header File :file_folder:

* lists.h: Header file containing definitions and prototypes for all
types and functions written for the project.

| Type/File          | Definition/Prototype                                                                   |
| ------------------ | -------------------------------------------------------------------------------------- |
| `struct list_s`    | <ul><li>`char *str`</li><li>`unsigned int len`</li><li>`struct list_s *next`</li></ul> |
| `typedef list_t`   | `struct list_s`                                                                        |
| `0-print_list.c`   | `size_t print_list(const list_t *h);`                                                  |
| `1-list_len.c`     | `size_t list_len(const list_t *h);`                                                    |
| `2-add_node.c`     | `list_t *add_node(list_t **head, const char *str);`                                    |
| `3-add_node_end.c` | `list_t *add_node_end(list_t **head, const char *str);`                                |
| `4-free_list.c`    | `void free_list(list_t *head)`                                                         |

## Tasks :page_with_curl:

Q0. 0-print_list.c : C function that prints all the  elements of a list_t list.
Q1. 1-list_len.c: C function that returns the number of elements in a linked list_t list.
Q2. 2-add_node.c: C function that adds a new node at the  beginning a of a list_t list.
Q3. 3-add_node_end.c: C function that adds a new node at the end of a linked list_t list.
Q4. 4-free_list.c: C function that frees a list_t list.
Q5. 100-first.c:  function that prints You're beat! and yet, you must allow,\nI bore my house upon my back!\n before the main function is executed.
Q6. 101-hello_holberton.as: 64-but assembly program that prints Hello, Holberton followed by a new line using only the print function witout interrupts.
