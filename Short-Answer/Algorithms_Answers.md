#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Constant O(1) - This example is O(1) because no matter what n is, it is completely unaffected by the size of the input.

b) Linear O(n) - This example is O(n) because the input size will increase and the runtime will grow with it.

c) Exponential O(c^n) -  This example is O(c^n) because as the input increases, the runtime will grow at a faster rate.

## Exercise II
# eggs break at floor f+
# wont break below f-
I think I need to iterate over the floors and compair that to which floor we are on floor f+/-.
If floor is < f any eggs that are thrown will be broken.
Otherwise, any eggs thrown off on floor > f will not be broken.
- I think the runtime complexity of this algorithm would be O(n) because with each iteration n will be checked for each level +/- and will remain the same size. 

  

