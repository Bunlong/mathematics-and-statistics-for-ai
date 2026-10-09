# Matrices

### What is matrices?

A matrix is a rectangular arrangement of numbers.

Example:

$$
A =
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
$$

and

$$
\mathbf{x} =
\begin{bmatrix}
2 \\
3
\end{bmatrix}
$$

Then:

$$
Ax =
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
\begin{bmatrix}
2 \\
3
\end{bmatrix}
$$

Calculating each row:

$$
Ax =
\begin{bmatrix}
1(2)+2(3) \\
3(2)+4(3)
\end{bmatrix}
$$

Therefore:

$$
Ax =
\begin{bmatrix}
8 \\
18
\end{bmatrix}
$$

Multiply each row of A by the vector x:

  * First row: 1(2)+2(3)=8
  * Second row: 3(2)+4(3)=18

This operation is called matrix-vector multiplication, which is fundamental to neural networks.


Example in real world?