# MatrixChainMultiplication
Saw a pattern an decided to replicate it. 
It may or may not be an exact replication of MCM, but I did it based it's behavior and not on pseudocode. 
Produces the same output either way.

The purpose of MCM is to find the optimal order to multiply matrices.
It's a great benefit to reduce the number of inner addition operations form matrix multiplication.
The difference is vast when taking into account matrix dimensions and/or number of matrices.

Designed to read input via initial array.
To use, simply edit the values inside to calculate minimal operations needed.

e.g.
Matrix - dimension
A1 - 30 x 35
A2 - 35 x 15
A3 - 15 x 5
A4 - 5 x 10
A5 - 10 x 20
A6 - 20 x 25

should be input as: [30, 35, 15, 5, 10, 20, 25], and
this will output the contents similar to usual MCM layout (check Google - MCM dynamic programming examples)
