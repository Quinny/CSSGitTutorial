# First year challenge - Statistics Library

Your challenge as a team is to write a small library that computes statistics
that operate on a pairs of [arrays](http://www.tutorialspoint.com/cprogramming/c_arrays.htm).  You may assume that the arrays **do not** contain repeat elements,
but they may be unsorted.

*Feel free to write the code in the language you are most comfortable with, but
the examples will be provided in C.*

The following functions must be implemented:

## Intersection Size

The number of common elements between two lists.

```c
int intersection_size(int a[], int b[], int n) {
  // Compute intersection size
  return 0;
}
```

### Sample input and output

```c
int a[] = {1, 2, 3};
int b[] = {9, 2, 0};
intersection_size(a, b, 3) == 1

int a[] = {0, 1, 2};
int b[] = {3, 4, 5};
intersection_size(a, b, 3) == 0
```

## Union Size

The number of unique elements between two lists.

```c
int union_size(int a[], int b[], int n) {
  // Compute union size
  return 0;
}
```

### Sample input and output

```c
int a[] = {1, 2, 3};
int b[] = {9, 2, 0};
union_size(a, b, 3) == 5

int a[] = {0, 1, 2};
int b[] = {3, 4, 5};
union_size(a, b, 3) == 6
```

## Jaccard Similarity

The intersection size divided by the union size.

```c

double jaccard_similarity(int a[], int b[], int n) {
  // Compute jaccard similarity
  return 0.0;
}
```

### Sample input and output

```c
int a[] = {1, 2, 3};
int b[] = {9, 2, 0};
jaccard_similarity(a, b, 3) == 0.2

int a[] = {0, 1, 2};
int b[] = {3, 4, 5};
jaccard_similarity(a, b, 3) == 0
```

## Hints

* Try to break up the work evenly.

* Write your code assuming that your partners code works correctly.

* Try to reuse functions, don't duplicate code!

* Write your code in separate branches, and then merge it when you are done.

* It may be useful to define a function that checks if a given element
belongs to an array, such as:

```c
int is_in_array(int a[], int n, int element) {
  // Returns 1 if element is in array, and 0 otherwise
  return 0;
}
```
