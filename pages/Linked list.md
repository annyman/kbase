- Dynamic array which allocates memory of **one node at a time**. It contains two fields: **data** and **pointer to the next** node.
- ## Byte sized algorithms:
	- #traversal
	  ```cpp
	  while(temp->next != NULL) { // reaching end of l.list
	    temp = temp->next;
	  }
	  ```
	- #insertion
	  ```cpp
	  temp->next = new Node; // adding node at end
	  temp->next->data = x;
	  temp->next->next = NULL;
	  ```