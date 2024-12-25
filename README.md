# AlgorithmTask
b. Analysis of Heapsort Algorithm

    Building the Max-Heap:
        The build_max_heap function iterates through all non-leaf nodes and calls the heapify function. The number of nodes in the heap is n.
        For each node, the heapify function performs comparisons and swaps in O(log n) time.
        The total time for building the max-heap is O(n), because the heapify operation works in O(log n) time and is performed on each of the n nodes.

    Sorting the Array:
        After building the max-heap, the algorithm extracts the maximum element (root of the heap) and places it at the end of the array. Each extraction requires O(log n) time for reheapifying the heap.
        Since there are n elements, the total time for sorting is O(n log n).

    Overall Time Complexity:
        Building the heap takes O(n).
        Sorting the heap takes O(n log n).
        Thus, the overall time complexity of heapsort is O(n log n).
        The space complexity is O(1), as heapsort is an in-place algorithm.
