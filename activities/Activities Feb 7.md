# MTH 302: Linear Algebra and Differential Equations

# Activities: 7 February 2023

## Part 1: Matrix inverses

1. Use SymPy to find the inverses of each of the following matrices, or determine that they aren't invertible: 

   (a) $\begin{bmatrix} 1 & 2 & -1 \\ 0 & 1 & 3 \\ 0 & 0 & 2 \end{bmatrix}$

   (b) $$\begin{bmatrix} 1 & -2 & -1 \\ -1 & 1 & 0 \\ 1 & 3 & 4 \end{bmatrix}$$

   (c) $\left[\begin{matrix}-5 & 3 & 6\\9 & 9 & -4\\3 & -9 & 0\end{matrix}\right]$

2. **(AA)** Use the result of part (c) above to solve the following linear system *without doing any row reduction at all*: 

$$-5x_1 +3x_2 +6x_3 = 5$$

$$9x_1 + 9x_2 -4x_3= 7$$

$$3x_1 -9x_2  = 3$$

Hint: If $A$ is the matrix from part (c) above, this system is the matrix-vector equation $A \mathbf{x} = \begin{bmatrix} 5 \\ 7 \\ 3 \end{bmatrix}$. Could you perform a certain operation to both sides of this equation to find $\mathbf{x}$? When you are done, **write one sentence to explain how inverses of matrices can be used to solve linear systems.** 

3. Consider these three matrices: 

   $$E_1 = \begin{bmatrix} 0 & 1 & 0 \\ 1 & 0 & 0 \\ 0 & 0 & 1 \end{bmatrix} \quad E_2 = \begin{bmatrix} 1 & 0 & 0 \\ 0  & 5 & 0 \\ 0 & 0 & 1 \end{bmatrix} \quad E_3 = \begin{bmatrix}1 & 0 & 0\\ 2 & 1 & 0\\ 0 & 0 & 1\end{bmatrix}$$

   Define these in SymPy, then create a random $3 \times 3$ matrix called $A$. Compute $E_1A$, $E_2A$, and $E_3A$. What effect does each matrix have on $A$ when it's multiplied to $A$? 

4. (Continuation of exercise 4) Without actually computing the inverse of each of the matrices in exercise 3, explain why you know each matrix is invertible, and make a guess as to what the inverse of each matrix is. (Then you can check your work on the computer.) 

---

## Part 2: Determinants

> Reminder: To find the determinant of `A` in SymPy, it's `A.det()`. 

1. Compute the determinants of matrices (a) and (b) in Part 1 by hand. The first one is much easier than the others; why is that?
2. A square matrix is *upper-triangular* if all the entries below the "main diagonal" are zero. For example, the matrix in (a) is upper-triangular. Copy the following into a code cell (you can find it here: https://gist.github.com/RobertTalbert/0d6042b7c5d88b5a0978b29cce7a670d) and execute it: 

```python
def randUT(n,lower,upper):
  A = randMatrix(n,n,lower,upper)
  for j in range(n-1):
    for i in range(j+1,n):
      A[i,j] = 0
  return A
```

This is a **function** in Python, which is what we call a custom command to do a computation. This particular function generates a random $n \times n$ upper-triangular matrix with entries between `lower` and `upper`. After executing the code, try out by running this code: 

```python
A = randUT(5, -10, 10)
A
```

Generate several upper-triangular matrices using this code; look at each matrix after you define it; then compute its determinant. **What is a quick way to find the determinant of an upper-triangular matrix?** Study your outputs, then fill in the blank: 

> If $A$ is upper-triangular then its determinant can be found by ____. 

3. **(AA)** What is the relationship between $\det(A)$, $\det(B)$, and $\det(AB)$? Make up some random matrices $A$ and $B$, compute each of those three quantities and compare them, then make a conjecture. 

4. If $A$ is an invertible matrix, what is the relationship between $\det(A)$ and $\det(A^{-1})$? Make up some random matrices and experiment. (You are almost certain to get an invertible matrix if you randomly generate one, but you might not. )