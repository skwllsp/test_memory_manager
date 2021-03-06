You are given a block of memory with several free and occupied blocks in it.

Your first task is to create a linked list of nodes with a) a pointer to the beginning of each free memory block and b) the length of the block.

The second task is to defragment the memory into a single block of free memory and a single block of occupied memory, preserving all data, using the linked list for iteration.

- Note: free memory is represented by 0. 
- Note: pieces of memory are not necessarily bytes (in this example they are integers), but are bitwise copyable. 
- Note: you cannot use any STL containers.

Full task description: https://github.com/skwllsp/test_memory_manager/blob/master/MemoryManager.pdf
