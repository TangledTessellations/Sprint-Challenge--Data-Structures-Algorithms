Add your answers to the questions below.

1. What is the runtime complexity of your `depth_first_for_each` method?
    The runtime complexity of my depht first for_each is O(n) because the algorithm must iterate of each item once.
2. What is the space complexity of your `depth_first_for_each` function?
    The space complexity of depth first for each is higher than the runtime complexity since the solution is recursive, and each and every time the function is called it will be forced to instantiate new variables and instances of the function itself. I still do not entirely know, but I'd have to guess that it's still closer to O(n) than O(n^2), our next increment up. 
3. What is the runtime complexity of your `breadth_first_for_each` method?
    Like depth first search, I'd have to guess O(n) because we are iterating over each item roughly one time. 
4. What is the space complexity of your `breadth_first_for_each` method?
    I'd guess also O(n), because we are not using recursion here and are simply changing the values of several variables.
5. What is the runtime complexity of your `heapsort` function?
    I believe O(n), because though we are using two for loops, the loops are not nested, leading each variable to be touched twice, or O(2n), which gets simplified down to O(n)
6. What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?
    I think the space complexity of this O(2n) since each item must be instantiated twice. If we were to alter the original array it would be O(n)