# MTH 302 Activities, January 31 

Work on these in groups. Activities labeled **AA** will be included in Application/Analysis 2, due on Wednesday February 8. 

## Part 1: Using Theorems 1.5.1 and 1.5.2

1. For each item below, determine whether the vector $\mathbf{b}$ is in the span of the columns of the matrix $\mathbf{A}$. If so, then determine weights that enable you to explicitly write $\mathbf{b}$ as a linear combination of the columns of $\mathbf{A}$. 

   (a) $\mathbf{b} = \begin{bmatrix} 6 \\ -20 \end{bmatrix}, \mathbf{A} = \begin{bmatrix} 4 & -1 \\ -12 & 3 \end{bmatrix}$

   (b)  $\mathbf{b} = \begin{bmatrix} -4 \\ -2 \\ -1 \end{bmatrix}, \mathbf{A} = \begin{bmatrix} 1 & 5 & -2 \\ 2 & -1 & 7 \\ -3 & 4 & -14 \end{bmatrix}$

2. **(AA)** Decide whether each of the following sentences is true or false. In every case, write one sentence to support your answer. If a statement is false, the best way to support it is to provide a specific example showing that the statement can be false. 

   (a) If $\mathbf{Ax = b}$ is consistent for at least one vector $\mathbf{b}$, then $\mathbf{A}$ has a pivot position in every row. 

   (b) If $\mathbf{A}$ is a $4 \times 3$ matrix, then it is possible for the columns of $\mathbf{A}$ to span $\mathbb{R}^4$. 

   (c) If $\mathbf{A}$ is a $3 \times 3$ matrix with *exactly* two pivot columns, then the columns of $\mathbf{A}$ do not span $\mathbb{R}^3$. 

   (d) If $\mathbf{A}$ is a $3 \times 4$ matrix, then the columns of $\mathbf{A}$ must span $\mathbb{R}^3$. 

## Part 2: Linear Independence 

1. In each item below, determine whether the given vectors are linearly independent or linearly dependent. 

   (a) $[3 \ {-2}]^T$ and $[9 \ {-6}]^T$

   (b) $[5 \ {-2}]^T, [5 \ 2]^T$, and $[11 \ {-5}]^T$ 

   (c) $[{-1} \ 2 \ 1]^T, [3 \ 1 \ 1]^T$, and $[1 \ 5 \ 3]^T$ 

2. For each of the sets of vectors in question 1, determine whether or not those vectors span $\mathbb{R}^2$ (in parts (a) and (b)) or $\mathbb{R}^3$ (in part (c)). *Hint*: No additional computations are necessary beyond those for the first question. 

3. Consider the differential equation $y''- y = 0$. This is called a *second-order* differential equation because it relates a function $y$ to its second derivative. A solution to this DE will be a function, $y(t)$, which when added to its second derivative, equals 0. 

   (a) Show by direct substitution that the functions $y_1 = e^t$ and $y_2 = e^{-t}$ are solutions to $y'' - y = 0$. 

   (b) Explain using graphs why $y_1 = e^t$ and $y_2 = e^{-t}$ are not scalar (constant) multiples of each other. Because these two functions are not scalar multiples of each other, we can reasonably call then "linearly independent functions". 

   (c) Show by direct substitution that any *linear combination* of $y_1$ and $y_2$ is also a solution to $y'' - y = 0$. That is, if $c_1$ and $c_2$ are any constants, then $y(t) = c_1 e^t + c_2 e^{-t}$ also solves the DE. 

   (d) *For reflection, not really a question:* It turns out (we'll learn why, later) that there are no other solutions to $y'' - y = 0$ other than linear combinations of $y_1$ and $y_2$. Therefore since $y_1$ and $y_2$ are "linearly independent" and every solution is a linear combination of them, we can say that the solutions to the DE are *spanned by* the functions $y_1 = e^t$ and $y_2 = e^{-t}$. The point: Linear algebra is the engine that drives a serious study of differential equations. 

4. **(AA)** It can be shown that all solutions of the second-order DE $y'' + y = 0$ are given by $y(t) = c_1 \sin(t) + c_2 \cos(t)$ where $c_1, c_2$ are arbitrary constants. (For practice: Show by direct substitution that $y(t)$ really solves this DE.) Suppose we know initial values for $y(0)$ and $y'(0)$ to be $y(0) = 4$ and $y'(0) = -2$. What are the values of $c_1$ and $c_2$? How is a system of linear equations involved? 