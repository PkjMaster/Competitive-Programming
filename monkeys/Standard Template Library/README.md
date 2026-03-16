# C++ Standard Template Library (STL)
## What is STL?
STL is a library that contains a lot of data structures and functions(algorithms), that help us to solve our problems.

## Main Structures

| Strucure | Description |
|----------|-------------|
| `vector` | Works like an array that allocates memory dynamically. But better 👌 |
| `set` | Store sorted unique values (crescente). |
| `map` | Store as "key/value" pairs. The value is accessed using the key |
| `pair` | Store a pair of values(that can be different data types). The value is acessed with `first` and `second`. |
| `stack` | Store elements according to LIFO (Last In, First Out), where we manipulate the data on top using `push`, `pop` and `top` |
| `queue` | Store elements according to FIFO (First In, First Out), where we insert data as the last value using `push`, and manipulate the first value using `pop` and `front`. |
| `priority_queue` | Store element based on a priority function, where by default is shown the biggest value first. Works like a queue, but the priority is more important than the order of insertion. To cchange the priority just add the parameter `greater<type>`:|
| `deque` | Just like a queue but can be manipulated on both sides `front` and `back`. And the elements can be accessed by index. |

## Main Algorithms
| Algorithm | Description |
|-----------|-------------|
| `sort` | Sort the elements of a strucure `sort(struc.begin(), struc.end());`. |
| `reverse` | Reverse sort the elements of a structure `reverse(struc.begin(), struc.end());`. |
| `swap` | Swap the value of two variables `swap(a, b)`.|


### References
Here is the references to study each of the main structures that the Monkeys group suggested.

* vector: https://www.geeksforgeeks.org/vector-in-cpp-stl/
* set: https://www.geeksforgeeks.org/set-in-cpp-stl/
* map: https://www.geeksforgeeks.org/cpp/map-associative-containers-the-c-standard-template-library-stl/
* pair: https://www.geeksforgeeks.org/pair-in-cpp-stl/
* stack: https://www.geeksforgeeks.org/stack-in-cpp-stl/
* queue: https://www.geeksforgeeks.org/queue-cpp-stl/
* priority_queue: https://www.geeksforgeeks.org/cpp/priority-queue-in-cpp-stl/
* deque: https://www.geeksforgeeks.org/deque-cpp-stl/


Here is the references to study each of the main algorithms that the Monkeys group suggested.

* sort: https://www.geeksforgeeks.org/sort-c-stl/
* reverse: https://www.geeksforgeeks.org/stdreverse-in-c/
* swap: https://www.geeksforgeeks.org/swap-in-cpp/
