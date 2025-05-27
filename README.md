# CSCI-GA.1180-Homework-Assignment-2-solution

Download Here: [CSCI-GA.1180 Homework Assignment 2 solution](https://jarviscodinghub.com/assignment/csci-ga-1180-homework-assignment-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Exercise 2.1. A square matrix A is symmetric if aij = aji.
(a) Find two specific symmetric square matrices A and B of dimension at least 2 × 2, with nonzero integer
entries, such that the product AB is not symmetric. Give A, B, and AB.
(b) Find two specific symmetric square matrices A and B of dimension at least 2 × 2, with nonzero integer
entries, whose product AB is symmetric. Give A, B, and AB.
(c) What condition is necessary in the 2 × 2 case for AB to be symmetric when A and B are symmetric?
Explain how you derived it.
Exercise 2.2. [Rank of a square triangular matrix.]
(a) Prove that a square upper-triangular matrix R is singular only if at least one diagonal element is zero.
(The same result is true for a lower-triangular matrix.)
(b) Assume that R is an n × n triangular matrix, and that k of its diagonal elements are zero. Must the
rank of R be exactly n − k? Explain your answer. If your answer is “yes”, give a proof. If your answer
is “no”, give a counterexample.
Exercise 2.3. Consider the n × n elementary matrix E = I − αxyT
.
(a) Show that E is singular if and only if αxTy = 1.
(b) If αxTy 6= 1, show that E−1 = I − βxyT
, where β = α/(αxTy − 1).
Exercise 2.4. Let x and y be n-vectors, and let Z be the rank-one matrix Z = xyT
. Describe an efficient
way to compute Z
k
(the k-th power of Z) for k > 1.
2
Exercise 2.5. Consider the following A and b:
A =


3 3 6
2 −3 6
1 6 0
2 0 1
6 3 0


and b =


4
3
1
−1
−5


.
(a) What is the rank of A? How did you determine this value? What conclusion do you draw about
whether the columns of A are linearly independent (or not)? Explain.
(b) Is b in the range of A? If your answer is “yes”, explain how you decided this. In this case, find the
coefficients in the linear combination such that b is a linear combination of the columns of A, and
explain how you found them. If your answer is “no”, explain your reasoning.
(c) Let r = rank(A). Find two subsets of r linearly independent rows of A (called “basic sets”), and
explain how you determined that the designated rows were linearly independent.
(d) Use these two basic sets to solve the system Ax = b for x, using a different basic set in each calculation
of x.
(e) Is x the same in both cases? Explain why or why not.
Exercise 2.6. [Properties of ATA.]
(a) If the columns of A are linearly independent, show that the matrix AT A is nonsingular.
(b) If A has linearly dependent columns, show that AT A is singular.
Exercise 2.7. Here are the four standard properties of the norm kAk of a real matrix A: (1) kAk > 0 if
A 6= 0, and k0k = 0; (2) kγAk = |γ| kAk for any scalar γ; (3) kA + Bk ≤ kAk + kBk for any B of compatible
dimensions; (4) kABk ≤ kAk kBk for any B of compatible dimensions.
(a) Show that the quantity M = maxi,j |aij |, i.e., the largest absolute value of any element in the matrix
A, satisfies properties (1), (2), and (3) of a matrix norm.
(b) Show that property (4) does not hold by giving a counterexample, i.e., specific matrices A and B such
that property (4) is not satisfied.
Exercise 2.8. [Properties of triangular matrices.] Show that the product of two square upper-triangular
matrices is upper triangular.
Exercise 2.9.
(a) Consider an n × n upper-triangular matrix U such that
u11u22 · · · un−1,n−1
6= 0, but unn = 0,
i.e., U is singular. Give a general algorithm for computing a nonzero vector x such that Ux = 0.
(b) Verify your algorithm by finding a solution x when U is given by
U =


1 −2
1
2
3 2
0

 .
(c) What is the general form of x satisfying Ux = 0 for this particular U?
