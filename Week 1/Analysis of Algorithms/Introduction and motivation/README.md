# Analysis of Algorithm

- It means measuring effiencincy of an algorithm

- It is done by measuring time and space complexity

- Time: How long the algorithm takes (running time)

- Space: Memory requirement

# Measuring Running time

- Analysis independent of underlying hardware
  - Don't use actual time
  - Measure in terms of "basic operations"

 What this means is that if we run a program on an outdated computer then it might take longer time than the one running on latest computer. So, this doesn't calculate the proficiency of the code written.
To solve that we will calculate running time in terms of basic operations.

- Typical basic operation
  - Compare two values
  - Assign a value to a variable
 
## Input Size

- Running time depends on input size
  - Larger arrays take longer to sort

- Measuring time efficiency as fuction of input size
  - Input size n
  - Running time t(n)
  - T(n): worst case estimate 

# Example 1: Sorting

- Sorting an array with n elements
  - Naive algorithms: time proportional to n<sup>2</sup>
  - Best algorithms: time proportional to n log n
 
