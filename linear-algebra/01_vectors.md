# Vectors


### What is vectors?

A vector is an ordered collection of numerical values.

Example:

$$
\mathbf{v} =
\begin{bmatrix}
2 \\
1
\end{bmatrix}
$$

This vector contains two components:

  * First component: 2
  * Second component: 3

We can interpret it geometrically as an arrow from the origin to the point (2,3).

In machine learning, a vector can represent the features of a data point.

Example, suppose we want to represent a house using two features:

$$
\mathbf{x} =
\begin{bmatrix}
120 \\
3
\end{bmatrix}
$$

Here:

  * 120 represents the house size in square meters.
  * 3 represents the number of bedrooms.

This is a simplified feature vector. Real machine-learning systems often use many more features.

### Vector Operations

Consider two vectors:

$$
\mathbf{a} =
\begin{bmatrix}
2 \\
3
\end{bmatrix}
\qquad
\mathbf{b} =
\begin{bmatrix}
4 \\
1
\end{bmatrix}
$$

Addition:

$$
\mathbf{a}+\mathbf{b}
=
\begin{bmatrix}
6\\
4
\end{bmatrix}
$$

Subtraction:

$$
\mathbf{a}-\mathbf{b}
=
\begin{bmatrix}
-2\\
2
\end{bmatrix}
$$

Scalar multiplication:

$$
\mathbf{3a} =
\begin{bmatrix}
6 \\
9
\end{bmatrix}
$$

