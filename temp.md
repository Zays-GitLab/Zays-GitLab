
1.  What is a data structure?
    
    A data structure organizes and stores data in a computer to enable efficient access and modification. Types include arrays, lists, stacks, queues, trees, graphs, etc. Python lists, for instance, are mutable, ordered data structures that can hold varied data types.
    
2.  The seven properties of a Python list:
    
    -   Order: Python lists remember the order of items inserted.
        
    -   Accessibility: Any item can be accessed using its index.
        
    -   Mutability: They are mutable, meaning items can be added, removed, or changed.
        
    -   Size flexibility: The size of a Python list can grow or shrink as needed.
        
    -   Diversity of contents: They can contain items of any data type, and a single list can
        
        contain items of different data types.
        
    -   Nesting: Lists can contain other lists.
        
    -   Duplicate entries: Lists can contain duplicate entries.
        
    They are similar to what we discussed in class.
        
    
    -   Reading - 1 steps
        
    -   Searching for a value not contained within the list - 100 steps
        
    -   Insertion at the beginning of the list - 101 steps
        
    -   Insertion at the end of the list - 1 step Amortized
        
    -   Deletion at the beginning of the list - 100 steps
        
    -   Deletion at the end of the list - 1 step
        
3.  Why do you need to study different data structures? Why is a list not sufficient?
    
    Different data structures cater to specific tasks and offer varied efficiency levels. Lists are versatile but not always efficient for operations like item searching. Other structures like trees and hash-based structures perform these tasks more efficiently. Advanced algorithms and systems often require specialized data structures like heaps, queues, or graphs.
    
4.  What is an algorithm?
    
    An algorithm is a step-by-step procedure for performing calculations or solving problems. In computer science, an algorithm is a sequence of steps or a set of rules that are followed to complete a task. This task can be anything from sorting a list of numbers to finding a path in a network or graph.
    
5.  Time complexity of algorithms is measured in terms of steps instead of pure time. Why is that?
    
    Time complexity, measured in steps, provides a machine-independent measure of algorithm efficiency. Unlike actual time, which varies across hardware and software, the step count remains consistent, allowing comparative efficiency evaluation across different computing environments.
    

6. We compared linear search to binary search. Which searching algorithm is better and why?

Binary search is generally more efficient than linear search, but it requires that the list be sorted. Sorting a list can be an expensive operation in terms of time complexity, so if the list is not already sorted, the cost of sorting needs to be taken into account. Binary search works by repeatedly dividing the list in half and discarding the half that does not contain the item, achieving a time complexity of O(log n). On the other hand, linear search works by sequentially checking each element in the list, resulting in a time complexity of O(n). Therefore, if the list is already sorted or if we need to perform many search operations, binary search is often the better choice.
