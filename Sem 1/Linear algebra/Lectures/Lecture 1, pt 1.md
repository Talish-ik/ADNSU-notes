**<mark>Matrices</mark>**- a rectangular array of real numbers.
The individual values on matrices are called Entries or Elements.
The general form of a matrix is written as
$$A_{mxn} = \begin{bmatrix} a_{1,1} & a_{1,2} & a_{1,3} \\ a_{2,1} & a_{2,2} & a_{2,3} \\ a_{3,1} & a_{3,2} & a_{3,3} \end{bmatrix}$$
Where m = n = number of rows and columns respectfully and are both equal to 3 in this specific example.
$A_{mxn} = (a_{i,j})$; i = 1,2,...,m; j = 1,2,...,n.
Examples:
$$A_{3x3} = \begin{bmatrix} 4 & 2 & 0 \\ 5 & -1 & 3 \\ -8 & 9 & 6 \end{bmatrix} \qquad or \qquad B_{4x1} = \begin{bmatrix} 4 \\ 3 \\ 2 \\ 1 \end{bmatrix} $$
## Types of matrices
1) Square matrices:
Number of rows = number of columns => m = n.
$A_{3x3} = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$ - square matrix of 3rd (n-th) order
Principal (main) diagonal elements are from top left to bottom right, here - 1, 5, 9; ↘ 
Secondary diagonal elements are from top right to bottom left, here - 3, 5, 7; ↙

2) Diagonal matrices:
Same as square, but all elements except diagonal are equal to zero
Diagonal - $a_{i,j} = 0$ when $i \neq j$

$A_{4x4} = \begin{bmatrix} 1 & 0 & 0 & 0 \\ 0& 5 & 0 & 0 \\ 0 & 0 & 3 & 0 \\ 0 & 0 & 0 & 7\end{bmatrix}$ - diagonal matrix of 4th order
Important: This matrix can only have elements from up left to down right, like in this example

3) Identity matrix
If in a diagonal matrix all main diagonal elements are equal to 1, then this matrix is called identity matrices
$A_{3x3} = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}$ - identity matrix of 3rd order

4) Zero matrix
If in a matrix of any size all the elements are equal to zero, then it is called the zero matrix
$\vec{0} = \begin{bmatrix} 0 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{bmatrix}; \begin{bmatrix} 0 \\ 0 \\ 0 \end{bmatrix}$; it can be of any size.
