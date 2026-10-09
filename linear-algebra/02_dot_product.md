# Dot Product

For two vectors:

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

Their dot product is:

$$
\mathbf{a}\cdot\mathbf{b} = (2 \times 4) + (3 \times 1)
$$

Therefore:

$$
\mathbf{a}\cdot\mathbf{b} = 8 + 3 = 11
$$

$$
\mathbf{a}\cdot\mathbf{b} = 11
$$

Why is this useful?

A simple linear regression model calculates predictions using a weighted sum of input features:

$$
\hat{y} = \mathbf{w} \cdot \mathbf{x} + b
$$

Where:

  * x is the input feature vector.
  * w is the weight vector.
  * b is the bias.
  * y^ is the predicted value.

The dot product combines the features with their corresponding weights.

Dot products also appear in neural networks, attention mechanisms, and vector similarity calculations.

Example:

$$
\mathbf{w} =
\begin{bmatrix}
2\\
3
\end{bmatrix}
\qquad
\mathbf{x} =
\begin{bmatrix}
4\\
1
\end{bmatrix}
\qquad
b = 5
$$

Calculate the prediction:

$$
\hat{y} = (2 \times 4) + (3 \times 1) + 5
$$

$$
\hat{y} = 8 + 3 + 5 = 16
$$

Result:

$$
\hat{y} = 16
$$
