# bigOnotes

### what is big o notation?
Big O notation is a way to describe the performance or efficiency of an algorithm in computer science. It helps us understand how an algorithm's running time (or space usage) scales with the size of the input data.

In simple terms, Big O notation tells us how fast or slow an algorithm will be as the amount of data it needs to process gets bigger. It provides an upper bound on the worst-case scenario for how the algorithm's performance will behave.


# O(1) - Constant Time:
This means that the algorithm's runtime doesn't depend on the input size; it takes the same amount of time regardless of how much data there is.

Example: Accessing an element in an array by its index. No matter how large the array is, accessing a specific element takes the same amount of time because it's a direct operation.

# O(n) - Linear Time: 
The algorithm's runtime scales linearly with the input size. If the input size doubles, the runtime roughly doubles as well.

Example: Scanning through an array to find a specific value. The more elements in the array, the longer it will take to find the value because you have to check each element one by one.

# O(n^2) - Quadratic Time: 
The runtime of the algorithm is proportional to the square of the input size. If the input size doubles, the runtime increases fourfold.

Example: Nested loops where you compare every element in a list to every other element. If you have 10 elements, you might need to make 100 comparisons (10 * 10).

# O(log n) - Logarithmic Time:
This is often associated with algorithms that repeatedly divide the input into smaller pieces. As the input size increases, the runtime doesn't increase as much because you're reducing the search space efficiently.

Example: Binary search in a sorted list. With each comparison, you eliminate half of the remaining elements. So, even with a large list, you find the target quickly.

# O(n log n) - Linearithmic Time: 
This is common in efficient sorting algorithms like Merge Sort and Quick Sort. The runtime is between linear and quadratic, making it more efficient than O(n^2) but not as fast as O(log n).

Example: Merge Sort divides the list into smaller pieces, sorts them individually, and then merges them back together.
