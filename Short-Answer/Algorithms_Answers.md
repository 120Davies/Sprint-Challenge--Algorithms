#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n), since it loops once through the data, scaling linearly with input size.


b) O(logn), in the while loop, the runtime will grow more slowly as n increases.


c) O(n) again, even though it's a recursive function, because it scales proportional to n. This is good code that allows for a quick runtime as n increases to large numbers.

## Exercise II

I think we should start with a binary search to look at the building floors as a sorted list, allowing us to find the highest floor without running the test on each floor individually. For example, in an (n) story building, we drop the egg from the (n//2)th story. If the egg breaks, we move down to (n//4), if it doesn't, we go up to (3n//4), and so on. This way we don't need to test most of the floors and saving lots of computation time. It would have a time complexity of O(logn).
