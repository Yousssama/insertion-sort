# insertion-sort
In this version of the algorithm, the for loop iterates over the elements of the input array, starting from the second element. For each element, the key variable is used to temporarily store the value of the current element being sorted. The j counter is initialized to the index of the element immediately before the current element.

The while loop iterates over the sorted subarray from right to left, moving each element up one position until the correct position for the current element is found. Once the correct position is found, the current element is inserted into the sorted subarray by setting arr[j+1] to the key value.

This algorithm uses two counters: i and j. The i counter is used to iterate over the elements of the input array and select the element to be inserted into the sorted subarray. The j counter is used to iterate over the sorted subarray and find the correct position to insert the selected element.

In this case, the j counter is used to traverse the sorted subarray in reverse order, comparing each element to the key value and moving it up one position until the correct position for the key value is found.
