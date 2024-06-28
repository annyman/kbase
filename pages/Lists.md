- A list in data structure is an **ordered collection of elements**, where each element can be accessed by its *index*. They are fundamental for organizing and manipulating data in various applications.
- ## Abstract view
  collapsed:: true
	- Static: [[Arrays]]
	  collapsed:: true
		- Stores a given **number** of elements of a **given data-type**.
		- **Write**/modify element at a **position**.
		- **Read** element at a position.
		- e.g. [[Arrays]] in C.
		- ```cpp
		  int a[10]; // initialisation
		  a[i] = 2; // declaration
		  cout<<a[i]; // print
		  ```
	- Dynamic: [[Linked list]]
	  collapsed:: true
		- Empty list has size 0
		- Insertion, deletion
		- Counting
		- Read/modify element at a position
		- Specify data type
		- Dynamic:
- ## [[Arrays]] vs. [[Linked list]]
  collapsed:: true
	- If data requires more memory, linked list will consume lesser memory overall compared to arrays
	- ||Array|Linked List|
	  |--|--|--|
	  |Memory requirements|- fixed size[:br]- large block of memory might not be available|- no unused memory[:br]- extra memory for pointer variables[:br]- memory available as multiple small blocks|
	  |Cost of accessing|`O(1)` const|`O(n)` linear|
	  |Cost of inserting/deleting|- at beginning `O(n)`[:br]- at end `O(1)`[:br]- at i'th position `O(n)`|- `O(1)`[:br]- `O(n)`[:br]- `O(n)`|
	  |Ease of use|Comes out of the box|Hard to setup|