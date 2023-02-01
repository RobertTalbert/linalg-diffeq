# MTH 302: Activities for Thursday February 2

## Part 1: Matrix algebra 

1. Below are some statements about matrix arithmetic. Some of these are true for all square matrices of the same size. Some of them, however, might be true for *some* square matrices of compatible sizes but not all. For each one, experiment by using SymPy to generate random square matrices of compatible sizes and performing the calculations. If you think the statement is true for all square matrices of compatible size, then say so and give a brief explanation that is not just an example. If you think the statement is not always true, then give two examples: One where the statement *is* true and another where it is *not* true. 

   (a) (The "commutative property" for addition) For all square matrices $\mathbf{A}$ and $\mathbf{B}$ of the same size, $\mathbf{A + B = B + A}$. 

   (b) (The "commutative property" for multiplication) For all square matrices $\mathbf{A}$ and $\mathbf{B}$ of the same size, $\mathbf{AB} = \mathbf{B}\mathbf{A}$. 

   (c) For all square matrices $\mathbf{A}$ and $\mathbf{B}$ of the same size, $(\mathbf{A + B})^T = \mathbf{A}^T + \mathbf{B}^T$. 

   (d) For all square matrices $\mathbf{A}$ and $\mathbf{B}$ of the same size, $(\mathbf{AB})^T = \mathbf{A}^T \cdot \mathbf{B}^T$. 

   (e) For all square matrices $\mathbf{A}$ and $\mathbf{B}$ of the same size and for any scalar $k$, $k(\mathbf{A + B}) = k\mathbf{A} + k\mathbf{B}$. 

   ---

   ## Part 2: Inverses 

   ![Screen Shot 2023-02-01 at 12.22.11 PM](/Users/roberttalbert/Desktop/Screen Shot 2023-02-01 at 12.22.11 PM.png)

2. Let $\mathbf{A}$ and $\mathbf{B}$ be square matrices that are invertible, so $\mathbf{A}^{-1}$ and $\mathbf{B}^{-1}$ both exist. It can be shown (but don't worry about it now) that the product $\mathbf{AB}$ is also invertible, so $(\mathbf{AB})^{-1}$ exists. Is $(\mathbf{AB})^{-1} = \mathbf{A}^{-1} \mathbf{B}^{-1}$? If not, give an example where the equality fails; then, by experimenting with matrices, find a formula for $(\mathbf{AB})^{-1}$ in terms of $\mathbf{A}$ and $\mathbf{B}$. 