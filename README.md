# PCS-2nd-assignment
benchmarking means comparing two code snippets to see which execute faster.
in my code:
it takes two inputs one is size and one is length and we have an empty list.
we have random.randint, it works like it gives us a random variable in the specific interval which for us is between 0 to length of the list(for example 100). we see that there is append,
it works like it appends a variable in the list in the interval that i put.

so we have two lists here , Length and Size as examples and I put variables in both
both have 4 variables,
so we call these two list in the next lines then the program will give us some random lists and take the time of both to check how much each of these two functions(quicksort and mergesort) take.


what I understood from this timeit code, its obvious that Quicksort is better and faster in most cases except in cases with big length and few ranges.
for example when we see length = 10000, and range=10 there is a sharp differences like quicksort is way more slower than mergesort or even with 1000 length and 10 ranges, there is a big difference between quicksort and mergesort which merge sort is quicker.


