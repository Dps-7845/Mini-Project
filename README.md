# Mini-Project
The code begins by including the necessary header files for input/output, string manipulation, and the map container. It also includes the algorithm header file for sorting purposes.

Next, a struct called Node is defined, which represents a node in the linked list. It contains a string data member and a pointer to the next node.

The insert function is defined to insert a new node at the beginning of the linked list. It takes the head pointer, the data to be inserted, and a map reference to keep track of word occurrences. Inside the function, a new node is created, its data is set to the input data, and its next pointer is set to the current head. The head pointer is then updated to point to the new node. Additionally, the word count in the map is incremented for the inserted data.

The displayList function is defined to display the sorted strings in the linked list. It takes the head pointer as input. Inside the function, an array called abc is created to store the strings from the linked list. The strings are extracted from each node and stored in the array. The size of the array is determined by counting the number of nodes in the linked list. The sort function is then used to sort the strings in ascending order. Finally, the sorted strings are displayed on the console.

In the main function, the head pointer and the wordCount map are initialized to nullptr and an empty map, respectively. The insert function is called multiple times to insert different words into the linked list and update the word count in the map. The displayList function is then called to display the sorted strings in the linked list. Finally, a loop is used to iterate over the wordCount map and print the words that are repeated more than once along with their respective counts
