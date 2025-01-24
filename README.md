the program will take a list of numbers and sort them for smallest to biggest
printValues(int* arr)
A pointer to an array of integers.
Steps:
Start a loop to iterate over the array elements.
Print each element in the array.
After printing all elements, print a newline.
prints array

swap(int* x, int* y)
Two integer pointers, x and y.
Steps:
Declare a temporary variable temp to store the value of *x.
Set *x = *y to copy the value of y into x.
Set *y = temp to copy the stored value of x (originally in temp) into y.
it mpdifies x and y

sort(int* arr)
A pointer to an array of integers.
Steps:
For i = 0 to MAX - 1 (this is the number of passes needed):
For j = 0 to MAX - 1 - i (this is the part of the array that still needs to be sorted):
If arr[j] > arr[j + 1], call swap(&arr[j], &arr[j + 1]) to swap the elements.
After MAX - 1 passes, the array will be sorted in ascending order.
it changes the order of the array

main()
no input
Steps:
Initialize the array values[] with the given numbers.
Print the unsorted array using printValues(values).
Test the swap function by swapping two integers (x and y).
Print the values of x and y before and after the swap.
Call sort(values) to sort the array using the bubble sort algorithm.
Print the sorted array using printValues(values).
Printed values showing the unsorted and sorted arrays, along with the swap test.
