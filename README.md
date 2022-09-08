## C-Linked-List-program. 


# Running the Program:

### Run the program inside any text editor like `VS code,` `ATOM,` Etc. However, you may have to install extensions. 

### Simplest way to run the program is using an IDE like Replit.com, where you can fork the repository and click the green RUN button to execute the code. 

### Replit link to Fork: `https://replit.com/join/jumqvjtcfv-iosvaldo`

## there are three different files the one you want to run is the `list.c` file.

### the prompts will guide you through choosing nodes
### entering each node number
### the final result will display the linked list. 


Summary:

The creation of a link. 
First, we ask the user how many nodes want to create and store inside a variable.
In the structure definition for the linked list, we are defining the structure typedef struct node to avoid using struct node every time. 
Next is the pointer to the same structure because a linked list is a self-reference data structure.

HEAD is used to store the address of the node. It's set to NULL at the start.

createdLInkedList is a simple function that creates the linked list

We declare three pointers head for the initial node, temp is a temporary node, and p is for adding the node to the correct position. 

We create a for loop that iterates through the nodes. 

We then create an individual node, which will temporarily store each node in the data.

Using Conditional Logic
If the head is still NULL, meaning the list is empty, we make temp the first node. 
For example, we have these nodes 13, 22, 34, 55, NULL ...& 75 represents the NULL & we want to attach. If the head is still NULL, meaning the list is empty, we make temp the first node. It is to the end of the node. We iterate a new variable to attach it. Using a conditional statement, we create a while loop that says while p ! = to the next node, then we link newly node to the end by assigning it to temp.

We then create a function to display the list called displayLinkedList to print the list. 

the head will start the first node, and while p->next = NULL and depending on the number and condition, it will print the next number or NULL
`dipsplayList(HEAD);`

** Program Resource: ``https://prepinsta.com/c-program/singly-linked-list/#:~:text=Implementation%20of%20Singly%20Linked%20List,be%20the%20next%20to%20it``


