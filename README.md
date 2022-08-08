# interview_study_plan

## Algorithms and Data Structures

- Dynamic Programming: https://www.youtube.com/watch?v=oBt53YbR9Kk
- Coursera algorithms: https://www.coursera.org/learn/algorithms-part1#syllabus
    - 6 weeks of lectures - implement as you go along
    - Make sure to implement the following data structures
        - Linked List
        - [Dynamic array](https://en.wikipedia.org/wiki/Dynamic_array), implemented with a [ring buffer](https://en.wikipedia.org/wiki/Circular_buffer) (use a statically sized array underneath the hood)
        - Hash set
        - [Hash map (with chaining)](https://en.wikipedia.org/wiki/Hash_table#Separate_chaining_with_linked_lists)
        - Binary heap (without decrease-key; know that [Fibonacci heaps](https://en.wikipedia.org/wiki/Fibonacci_heap) exist and know their guarantees)
        - Binary search tree (doesn’t need to be self-balancing; know that [self-balancing trees](https://en.wikipedia.org/wiki/Self-balancing_binary_search_tree#Implementations) exist and know their guarantees)
        - Prefix tree (a.k.a. trie)
        - Suffix tree (don’t worry about compression, just build a dumb version; know that [Ukkonen’s algorithm](https://en.wikipedia.org/wiki/Ukkonen%27s_algorithm) exists and learn its guarantees)
        - An object-oriented [adjacency list](https://en.wikipedia.org/wiki/Adjacency_list) for graphs
    - Implement the following algorithms
        - Binary search (implement it both iteratively and recursively)
        - Randomized quicksort (pay extra attention to the partition subroutine, as it’s useful in a lot of places)
        - Mergesort
        - Breadth-first search in a graph
        - Depth-first search in a graph (augment it to detect cycles)
        - Tree traversals (pre-order, in-order, post-order)
        - Topological sort (using [Tarjan’s algorithm](https://en.wikipedia.org/wiki/Topological_sorting#Depth-first_search))
        - Dijkstra’s algorithm ([without decrease-key](https://stackoverflow.com/questions/9255620/why-does-dijkstras-algorithm-use-decrease-key))
        - Longest common subsequence (using dynamic programming with matrices)
        - Knapsack problem (also dynamic programming)
    - Know time complexities (see [cheat sheet](https://www.bigocheatsheet.com/))
- The algorithm design manual: https://mimoza.marmara.edu.tr/~msakalli/cse706_12/SkienaTheAlgorithmDesignManual.pdf - Read section I
- Miscellaneous
    - Understand heap sort
    - Quick select
    - Median of medians
    - Bit manipulation
    - Assembly (high level) - see this [video](https://www.youtube.com/watch?v=RZUDEaLa5Nw)
