#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) 0(n) since a = 1 would just be 0(1). But in a while loop, it appears there are 3n which is linear.


b) 0(n^2) since it appears that there are like two loops. One loop is nested within another. sum = 0 is a 0(n) as sum += i and j += 2. The for and while are 0(n) and 0(n) and multiplying them togther is 0(n^2).


c) 0(n) since in this recursive function that would run n or bunnies times before it reaches a base case. Which makes this linear

## Exercise II


If there is n-story with eggs in them, f = number of floors. If f is higher, the eggs get broken. If f is smaller, the egg won't break. This can be approached by using a binary tree where the greater f value goes to the right and the lesser f value goes to the left. And the runtime complexity for a binary search tree is 0(log n) but its worst case can be 0(n).