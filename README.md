# MOLSIP2341-Intern-Pinaki_General_Revision
![Presentation1](https://github.com/PINAKIMATHAN/MOLSIP2341-Intern-Pinaki_General_Revision/assets/107812574/bea53eb5-2458-40f5-a164-406547ee0bed)


These are just some of the basic methods for these data structures in Python. Keep in mind that Python has a rich standard library, and there are more methods and functionalities available for each data structure.
# 1. List:
Creating a list

my_list = [1, 2, 3, 4, 5]

Methods

my_list.append(6)       # Add an element to the end

my_list.extend([7, 8])  # Extend the list by appending elements from the iterable

my_list.insert(2, 10)   # Insert an element at a specific index

my_list.remove(3)       # Remove the first occurrence of a value

popped_value = my_list.pop()  # Remove and return the last element

index = my_list.index(4)      # Return the index of the first occurrence of a value

count = my_list.count(5)      # Return the number of occurrences of a value

my_list.sort()          # Sort the list in ascending order

my_list.reverse()       # Reverse the elements of the list

--------------------------------------------------------------------------------------------------------------------------------
# 2. Tuple:
Creating a tuple

my_tuple = (1, 2, 3, 4, 5)

Tuples are immutable, so they have fewer methods compared to lists

index = my_tuple.index(3)  # Return the index of the first occurrence of a value

count = my_tuple.count(5)  # Return the number of occurrences of a value

--------------------------------------------------------------------------------------------------------------------------------
# 3. Set:
Creating a set

my_set = {1, 2, 3, 4, 5}

Methods

my_set.add(6)        # Add an element to the set

my_set.update({7, 8})  # Update the set with elements from another iterable

my_set.remove(3)     # Remove an element from the set; raises KeyError if not present

my_set.discard(4)    # Remove an element from the set if present

popped_value = my_set.pop()  # Remove and return an arbitrary element

--------------------------------------------------------------------------------------------------------------------------------
# 4. Dictionary:
Creating a dictionary

my_dict = {'one': 1, 'two': 2, 'three': 3}

Methods

my_dict['four'] = 4       # Add a new key-value pair

value = my_dict.get('two')  # Get the value associated with a key

keys = my_dict.keys()      # Return a list of all keys

values = my_dict.values()  # Return a list of all values

items = my_dict.items()    # Return a list of key-value tuples

my_dict.pop('three')       # Remove a key-value pair; raises KeyError if not present

my_dict.popitem()          # Remove and return an arbitrary key-value pair as a tuple

--------------------------------------------------------------------------------------------------------------------------------
# 5. String:
Creating a string

my_string = "Hello, World!"

Methods

upper_case = my_string.upper()         # Convert the string to uppercase

lower_case = my_string.lower()         # Convert the string to lowercase

length = len(my_string)                # Return the length of the string

substring = my_string[0:5]             # Get a substring

replaced_string = my_string.replace('Hello', 'Hi')  # Replace occurrences of a substring

split_list = my_string.split(', ')     # Split the string into a list based on a delimiter

joined_string = ', '.join(split_list)  # Join a list of strings into a single string

--------------------------------------------------------------------------------------------------------------------------------
# 6. Array Data Structure:
Creating an array (list)

my_array = [1, 2, 3, 4, 5]

Methods

my_array.append(6)      # Add an element to the end

my_array.extend([7, 8]) # Extend the array by appending elements from the iterable

my_array.insert(2, 10)  # Insert an element at a specific index

my_array.remove(3)      # Remove the first occurrence of a value

popped_value = my_array.pop()  # Remove and return the last element

--------------------------------------------------------------------------------------------------------------------------------
# 7. Linked List Data Structure:
class Node:

    def __init__(self, data):
    
        self.data = data
        
        self.next = None

Creating a linked list

node1 = Node(1)

node2 = Node(2)

node3 = Node(3)

node1.next = node2

node2.next = node3

--------------------------------------------------------------------------------------------------------------------------------
# 8. Stack Data Structure:
Creating a stack

my_stack = []

Methods

my_stack.append(1)    # Push an element onto the stack

my_stack.pop()        # Pop the top element from the stack

--------------------------------------------------------------------------------------------------------------------------------
# 9. Queue Data Structure:
from collections import deque

Creating a queue using deque

my_queue = deque()

Methods

my_queue.append(1)     # Enqueue an element

my_queue.popleft()     # Dequeue the front element

--------------------------------------------------------------------------------------------------------------------------------
# 10. Heap Data Structure:
import heapq

Creating a heap

my_heap = [3, 1, 4, 1, 5, 9, 2]

Methods

heapq.heapify(my_heap)  # Convert the list into a heap

heapq.heappush(my_heap, 6)  # Push an element onto the heap

popped_value = heapq.heappop(my_heap)  # Pop the smallest element from the heap

--------------------------------------------------------------------------------------------------------------------------------
# 11. Hashing Data Structure:
Creating a dictionary (hash table)

my_dict = {'one': 1, 'two': 2, 'three': 3}

Methods

value = my_dict.get('two')  # Get the value associated with a key

keys = my_dict.keys()        # Return a list of all keys

values = my_dict.values()    # Return a list of all values

--------------------------------------------------------------------------------------------------------------------------------




