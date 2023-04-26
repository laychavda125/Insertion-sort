# DSC SORT-Insertion-Code

Description:
This C program performs the insertion sort algorithm on an integer array. The InsertionSort function sorts the elements of the array in ascending order using the insertion sort algorithm. The main function initializes an integer array with values, calls the InsertionSort function to sort the array, and then prints the sorted array to the console.

Algorithm:

Define the InsertionSort function that takes an integer array and its size as arguments.
Initialize three integer variables, i, j, and small, used as loop counters and for comparison purposes.
Iterate over the array using the outer loop variable i.
Set the small variable equal to the current array element arr[i].
Iterate over the sorted portion of the array using the inner loop variable j.
While j is greater than or equal to zero and the current sorted element is greater than the small element:
a. Set the next element in the array to the current sorted element.
b. Decrement j.
Set the next element in the array to the small element.
Repeat steps 4-7 for each unsorted element in the array.
The array is now sorted in ascending order.
Output:
The output of this program will be the sorted array, printed to the console. In this case, the output will be:
4 7 8 23 56
