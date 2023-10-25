# MINI-PROJECT
This C++ program defines a linked list of strings and performs the following tasks:
It allows you to input a list of words (strings).
Inserts each word at the end of the linked list.
Sorts the linked list in alphabetical order.
Reports repeated words in the linked list.


struct Node: Defines a structure for a node in the linked list, containing a string (data) and a pointer to the next node (next).

insert: Inserts a new node with the given string value at the end of the linked list.

sortLinkedList: Sorts the linked list in alphabetical order. It does this by first copying the data from the linked list into a standard C++ list<string>, sorting that list, and then copying the sorted data back to the linked list.

reportRepeatedWords: Reports repeated words in the linked list. It uses two lists, one for unique words and another for repeated words. As it iterates through the linked list, it checks if the word is already in the uniqueWords list. If it is, the word is added to the repeatedWords list.

In the main function:

It takes the number of words as input and then takes each word as input and inserts it into the linked list.
It sorts the linked list.
It prints the sorted list of words.
It calls the reportRepeatedWords function to print the repeated words in the list.
Finally, it cleans up the memory by deleting all nodes in the linked list to prevent memory leaks.
