#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) - Linear runtime because there is 1 while loop that runs as long as a is less than n^3 and will increase a bu n^2. Because of this they will cancel out to O(n)

b) O(log n) - the first loop is O(n) but the second runs an operation based off the the value of j which will double as it runs.

c) O(n) - the recursive function looks at the value stored in bunnies and only returns if bunnies = 0, else it will do some calculation and return the function. The runtime is O(n) because the function only runs a single operation depending on the value of bunnies.

## Exercise II

So to do this I would do a binary search. I would start at the halfway point and we know if the egg breaks we are too high, if not your too low. If the egg drops from this point, breaks = true, move on to the lower floors and start from that half way point. If the egg doesn't drop at the initial halfway point, break = false and move to the higher floors and drop from that halfway point. Continue until f is found. This would make the runtime O(log n)
