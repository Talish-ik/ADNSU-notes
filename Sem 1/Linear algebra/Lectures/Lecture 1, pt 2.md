**<mark>Operations on matrices</mark>**
1) Addition.
Sum of two matrices A+B with same sizes is a matrix C, which elements are $c_{i,j} = a_{i,j} + b_{i,j}$
Example:
$A_{2x3}=\begin{bmatrix} 1 & 7 & -3 \\ 3 & 5 & -2 \end{bmatrix} \quad B_{2x3} = \begin{bmatrix} 7 & 2 & -5\\ 1 & 0 & -7 \end{bmatrix} \quad C_{2x3} = \begin{bmatrix} 8 & 9 & -8 \\ 4 & 5 & -9 \end{bmatrix}$

---
2) Scalar multiplication.
Scalar multiplication of number lambda $\lambda$ by matrix A equal $B = \lambda A$
$A_{3x2} = \begin{bmatrix} 5 & -4 \\ 7 & -6 \\ -1 & 9 \end{bmatrix}$                             $B_{3x2} = (-8)*A = \begin{bmatrix} -40 & 32 \\ -56 & 48\\ 8 & -72 \end{bmatrix}$

---
3) Subtraction
Subtraction of two matrices A and B with the same sizes can be found as $C=A-B$ or C=A+((-1)\*B)
$A_{2x2} = \begin{bmatrix} 1 & 7  \\ 8 & -9 \end{bmatrix}$     $B_{2x2} = \begin{bmatrix} -2 & -5 \\ 3 & 6 \end{bmatrix}$  $C_{2x2} = A-B =\begin{bmatrix} 3 & 12 \\ 5 & -15 \end{bmatrix}$
---
4) Multiplication of matrices
Multiplication of 2 matrices A and B is possible when the number of columns of first matrix A is equal to the number of rows in the second matrix B
$A_{mxn}*B_{mxn}$ will not be possible
$A_{mxn}*B_{nxp}$ is possible and is equal to $C_{mxp}$
$A_{3x2} * B_{2x2} = \begin{bmatrix} 4 & -3 \\ -5 & -7 \\ -1 & 2 \end{bmatrix} * \begin{bmatrix} 4 & 3 \\ -2 & 1 \end{bmatrix} = \begin{bmatrix}         22 & 9 \\ -6 & -22 \\ -8 & -1 \end{bmatrix} = C_{3x2}$ 
The calculation process:
You multiply ($a_{1,1}$ * $b_{1,1}$) + ($a_{1,2}$ * $b_{2,1}$), then you sum them and input to $c_{1,1}$
$(a_{1,1} * b_{1,2}) + (a_{1,2}*b_{2,2})$ and input to $c_{1,2}$
$(a_{2,1} * b_{1,1}) + (a_{2,2}*b_{2,1})$, and input to $c_{2,1}$
$(a_{2,1} * b_{1,2}) + (a_{2,2}*b_{2,2})$ and input to $c_{2,2}$ and so on.

---
5) Transpose of a matrix
Transpose of a matrix $A$ is denoted as $A^T$ 
$A_{2x3} = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{bmatrix}$; then $A^T_{3x2} = \begin{bmatrix} 1 & 4 \\ 2 & 5\\ 3 & 6 \end{bmatrix}$
