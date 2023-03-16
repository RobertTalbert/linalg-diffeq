# MTH 302: Linear algebra and differential equations

## Activities for Thursday, March 16 

### Part 1

Look at the system of DE's

$$\mathbf{x}' = \begin{bmatrix} 1 & 2 \\ 3 & 2 \end{bmatrix} \mathbf{x}$$

The eigenvalue-eigenvector pairs of the matrix here are $\lambda_1 = -1, \mathbf{v}_1 = [-1,1]^T$ and $\lambda_2 = 4, \mathbf{v}_2 = [2,3]^T$ . (If you are not sure how to find these using a computer, pause and try it, or ask a question.)

1. Give the two straight-line solutions for this system. 
2. Write the general solution for this system. 
3. Now let's think about how the solutions to this system behave over long periods of time. [You can click here](https://homepages.bluffton.edu/~nesterd/apps/slopefields.html?flags=2&dxdt=x+2y&dydt=3x+2y&x=-4,4,20&y=-3,3,15&method=rk4&h=0.1&lockT=0) for the direction field or "phase plane". By plotting them, describe the long-term behavior of the particular solutions with these initial conditions: $\mathbf{x}(0) = [1,1]^T$, $\mathbf{x}(0) = [0,2]^T$, and $\mathbf{x}(0) = [3,0]^T$. (Click on the "Initial points" button to enter a specific initial condition.)
4. Now plot the solution that has $\mathbf{x}(0) = [-1,1]^T$. What's different? What do you think the long-term behavior of this solution is, based on the phase plane plot? 
5. Using the general solution from question 2, solve the IVP that has $\mathbf{x}(0) = [-1,1]^T$. What is the long-term behavior of *this* solution? You should be able to tell without graphing. 
6. True or false: $(0,0)$ is a stable equilibrium point for this system. 



### Part 2: Equilibrium points

We've just learned that the trajectory of a non-equilibrium solution to a linear homogeneous system of first-order DEs is dependent on the signs (positive/negative) of the eigenvalues of its matrix. Use this fact to give examples with linear, homogeneous systems of DEs that have the following characteristics: 

1. The system has **two straight-line solutions**, and all non-equilibrium solutions move **away from** the origin over time
2. The system has **two straight-line solutions**, and all non-equilibrium solutions move **toward** the origin over time
3. The system has **no straight-line solutions**, and all non-equilibrium solutions move **away from** the origin over time
4. The system has **no straight-line solutions**, and all non-equilibrium solutions move **toward** the origin over time
5. (*Challenge*!) The system has **no straight line solutions**, and all non-equilibrium solutions **orbit** the origin in a circular pattern that neither approaches nor moves away from the origin. 

We've already seen an example of a system that has two straight-line solutions, and its non-equilibrium solutions sometimes move toward the origin over time but sometimes move away, depending on the initial condition: 

$$\mathbf{x}' = \begin{bmatrix} 1 & 2 \\ 3 & 2 \end{bmatrix} \mathbf{x}$$

One way to get these examples, if you can't find any we've already seen, is to use the `randMatrix` function in SymPy to generate some random $2 \times 2$ matrices. Every $2 \times 2$ matrix corresponds to a linear homogeneous system of DE's. Once you have your matrix, you can either plot the corresponding system in the phase plane; or you can use a computer to get information about the matrix which you can then use to tell the number of straight line solutions and classify the behaviors. 

*Example of use*: The following generates a random $2 \times 2$ matrix with values between $-10$ and $10$: 

```python
randMatrix(2,2,-10,10)
```



### Part 3: Putting it all together 

1. **(AA7)** Consider the system of differential equations $\mathbf{x}' = A\mathbf{x}$ given by $A = \begin{bmatrix} 2 & -1 \\ 3 & -2 \end{bmatrix}$. 

   (a) Determine the general solution to the system. 

   (b) Find all equilibrium points to the system and classify each one (stable/sink, unstable/source, saddle point, stable spiral, unstable spiral, or center). 

   (c) By hand, sketch the straight-line solutions to the system with the trajectories indicated. Then use these to plot a few nonlinear trajectories in the phase plane.

2.  Consider the system of differential equations $\mathbf{x}' = A\mathbf{x}$ given by $A = \begin{bmatrix} 3 & 1 \\ 1 & 3 \end{bmatrix}$. 

   (a) Find the general solution. 

   (b) Find the particular solution if $\mathbf{x}(0) = [-3, 1]^T$. 

   (c) Find and classify the equilibrium points. 

   (d) Sketch the straight-line solutions and a few nonlinear trajectories. 