#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Runtime complexity is O(n) because n is increasing in a linear relationship with each step.

b) O(log(2)) Logarithmic time complexity. The j variable is defined in the for loop, followed buy a while loop. j increments exponentially.

c) O(n) another example of linear time complexity decrementing bunnies step by step.


## Exercise II
f is unknown, and each floor is on top of the other (therefore sorted), we can use binary search to determine which floor f corresponds to while breaking the least amount of eggs.

function floor_f(takes range of floors): if range of floors is 1: return number of floors

at range of floors / 2
    if unbroken:
        floor_f(passing: range of floors / 2 as lowest, range of floors max)
    if broken:
        find_f(passing: range of floors min, range of floors / 2 as highest )