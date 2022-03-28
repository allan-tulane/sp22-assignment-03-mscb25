# CMPS 2200 Assignment 3
## Answers

**Name:**_____Maddie Bonanno____________________


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**

work and span:
first line = recursive call to parens_update --> W(n-1); S(n-1)
second line = constant time --> +1; +1

W(n) = W(n-1) + 1 //// S(n) = S(n-1) + 1

thus, W(n) exists in O(n) and S(n) exists in O(n)


- **d.**

work and span: --> 2(n/2) + 2(n/2) + n /// (n/2) + constants

W(n) = 4W(n/2) + n --> O(n log n)
S(n) = S(n/2) + 1 --> O(log n)


- **f.**

work and span: splitting in twice --> 2W(n/2)

W(n) = 2W(n/2) + n exists in O(n)
S(n) = S(n/2) + n exists in O(log n)