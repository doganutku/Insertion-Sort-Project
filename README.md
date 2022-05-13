[22,27,16,2,18,6] -> Insertion Sort

1-Write the steps about the insertion sort o that series above.
--

	[2,27,16,22,18,6]

	[2,6,16,22,18,27]

	[2,6,16,18,22,27]

	[2,6,16,18,22,27]

2-Write the Big-O Notation.
--
	n represents the size of the list,
	first step checking "n" amount of number
	after that, in every step "n" is decreasing "n", "n-1", "n-2"...
	"n"+"n-1"+"n-2"+...+1= ((n)*(n+1))/2= (n^2+n)/2
	so O(n^2)

3-Time Complexity: 
--
    Average case: The number can be placed in the middle which we are looking for.
    Worst case: The number can be placed in the end which we are looking for.
    Best case: The number can be placed in the very beginning of the line which we are looking for.

4-After the sorting, what is the type of time complexity of number 18?
--
	After the sorting, number 18 is in the middle, so it is avarage case scenario.


5-[7,3,5,8,2,9,4,15,6] Write the 4 steps of insertion sort of that series.
--
	[2,3,5,8,7,9,4,15,6]
	[2,3,5,8,7,9,4,15,6]
	[2,3,4,8,7,9,5,15,6]
	[2,3,4,5,7,9,8,15,6]
