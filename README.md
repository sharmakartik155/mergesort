# mergesort
Class 340 assignment last question:;

-merge sort is often done recursively;
-using divide and conquer tactics;
-time complexity: O(N*log(N));
-height of its tree is log(N);
-merging N elements for each and every level of the tree.;

take this array for example: 3 9 6 4 10 5 2 8;
becomes : 3 9 6 4      10 5 2 8;
becomes : 3 9     6 4      10 5     2 8;
becomes : 3    9     6   4      10    5     2    8;
sorting begins as with recursion;
becomes : 3 9     4 6      5 10     2 8;
becomes : 3 4 6 9     2 5 8 10;
becomes : 2 3 4 5 6 8 9 10;
Finally: 2 3 4 5 6 8 9 10 array is fully sorted;

Code Used: in mergesort.txt;
