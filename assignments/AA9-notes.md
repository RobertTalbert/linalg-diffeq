On Application/Analysis 9 you are asked to apply the "Method of Undetermined Coefficients" to find the general solution for the nonhomogenous system

$$\mathbf{x}'(t) = \begin{bmatrix} 2 & -1 \\ 3 & -2 \end{bmatrix} \mathbf{x}(t) + \begin{bmatrix} \cos(3t) \\ 4 \end{bmatrix}$$ 

As a reminder, this method for solving nonhomogeneous systems is 

1. Solve the homogeneous version of the system first;
2. Find a particular solution to the full nonhomogeneous system; and then
3. Add the results of (1) and (2). 

Step (2) involves making a reasonable guess as to the form of the particular solution, using a handful of undetermined constants, and then evaluate the guess into the left and right sides of the system which results in a system of linear equations which we then solve using linear algebra to find the values of the undetermined constants. 

In class, I pointed out that this problem was very similar to Example 3.6.2 in the textbook, which uses a guess of 

$$\mathbf{x}_p = \begin{bmatrix} a \cos(2t) + b \sin(2t) \\ c \cos(2t) + d \sin(2t) \end{bmatrix}$$



Anyone who found the homogeneous solution correctly, then made a reasonable guess for the particular solution and found appropriate values of the undetermined constants, then added the two solutions, received a Success mark on this – *even though simply mimicking the book's guess verbatim does not lead to a correct solution.* 

If you have a "Retry" on this, or are simply curious to know how the solution might go, keep reading. 

Based just on what the book says, you might start with 

$$\mathbf{x}_p = \begin{bmatrix} a \cos(3t) + b \sin(3t) \\ c \cos(3t) + d \sin(3t) \end{bmatrix}$$

since this problem's "add-on" vector involves $\cos(3t)$ just like the book's example has $\cos(2t)$. What's different here is the presence of the $4$ in the second component. **If you just use the above guess for $\mathbf{x}_p$, you will not be able to set up an appropriate system to solve**, because you'll be unable to account for the 4. In the book's example, it was a 0 and so the system was possible to set up. 

So you have to be more creative with the guess. You definitely need to keep sine and cosine terms in the guess as above, because once the derivative $\mathbf{x}'$ is taken, there need to be cosines and sines present to be equal to the right side. But since there is a 4 in the add-on vector, we need something extra. 

When the add-on vector was just a constant, like in the examples in class, we guessed that the particular solution must also be a constant vector. So, here, it makes sense to **add constants to the end of the first guess**, to get: 

$$\mathbf{x}_p = \begin{bmatrix} a \cos(3t) + b \sin(3t) + c\\ d \cos(3t) + e \sin(3t) + f \end{bmatrix}$$

(Here $e$ is not the number $e$, but an undetermined constant.)

Now, if you run this guess through the derivative on the left of the system and the arithmetic on the right, you'll end up, on the right, with a vector that has added constants in it, sufficient for finding a workable particular solution. The cost is that we now have two additional unknowns to deal with, so we should expect to have to work with a $6 \times 6$ system instead of $4 \times 4$. 

If you are retrying this one, you're expected to use this guess as your starting point. 