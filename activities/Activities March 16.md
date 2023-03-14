# MTH 302: Linear algebra and differential equations

## Activities for Thursday, March 16 

### Part 1: Equilibrium points

We've just learned that the trajectory of a non-equilibrium solution to a linear homogeneous system of first-order DEs is dependent on the signs (positive/negative) of the eigenvalues of its matrix. Use this fact to give examples with linear, homogeneous systems of DEs that have the following characteristics: 

1. The system has **two straight-line solutions**, and all non-equilibrium solutions move **away from** the origin over time
2. The system has **two straight-line solutions**, and all non-equilibrium solutions move **toward** the origin over time
3. The system has **no straight-line solutions**, and all non-equilibrium solutions move **away from** the origin over time
4. The system has **no straight-line solutions**, and all non-equilibrium solutions move **toward** the origin over time
5. (*Challenge*!) The system has **no straight line solutions**, and all non-equilibrium solutions **orbit** the origin in a circular pattern that neither approaches nor moves away from the origin. 

We've already seen an example of a system that has two straight-line solutions, and its non-equilibrium solutions sometimes move toward the origin over time but sometimes move away, depending on the initial condition: 

$$\mathbf{x}' = \begin{bmatrix} 1 & 2 \\ 3 & 2 \end{bmatrix} \mathbf{x}$$

*Suggestion*: Use the `randMatrix` function in SymPy to generate some random $2 \times 2$ matrices. Every one you generate corresponds to a system of DEs. If you generate a random matrix and make a system of DEs out of it, how might you easily tell what the behavior of its solutions is? 

*Example of use*: The following generates a random $2 \times 2$ matrix with values between $-10$ and $10$: 

```python
randMatrix(2,2,-10,10)
```



### Part 2: Putting it all together 

1. **(AA7)** Consider the system of differential equations $\mathbf{x}' = A\mathbf{x}$ given by $A = \begin{bmatrix} 2 & -1 \\ 3 & -2 \end{bmatrix}$. 

   (a) Determine the general solution to the system. 

   (b) Find all equilibrium points to the system and classify each one (stable/sink, unstable/source, saddle point, stable spiral, unstable spiral, or center). 

   (c) By hand, sketch the straight-line solutions to the system with the trajectories indicated. Then use these to plot a few nonlinear trajectories in the phase plane.

2.  Consider the system of differential equations $\mathbf{x}' = A\mathbf{x}$ given by $A = \begin{bmatrix} 3 & 1 \\ 1 & 3 \end{bmatrix}$. 

   (a) Find the general solution. 

   (b) Find the particular solution if $\mathbf{x}(0) = [-3, 1]^T$. 

   (c) Find and classify the equilibrium points. 

   (d) Sketch the straight-line solutions and a few nonlinear trajectories. 