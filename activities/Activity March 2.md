# MTH 302: Linear Algebra and Differential Equations

## Activity for Thursday, 2023-03-02

### Setup 

Imagine a block, hanging vertically from a spring. 

![Visualizing Mechanics: Natural Frequency of a Spring-Mass System - YouTube](https://i.ytimg.com/vi/lZPtFDXYQRU/maxresdefault.jpg)If the system is at rest, then there are two forces at work in the system that cancel leach other out: The downward force of gravity, given by $F_g = mg$ ($m$ is the mass of the block and $g$ is acceleration due to gravity) and $F_s = kL_0$ where $L_0$ is the length of the spring when it's stretched out by the block, and $k$ is a proportionality constant. (This second equation comes from Hooke's Law which says that the restoring force exerted by a spring is proportional to the distance it's stretched.) 

Now suppose that someone or something comes along and pulls on the block and lets it go. Visually, the mass will bob up and down but eventually come to rest. But at any given moment, the mass is undergoing acceleration. Newton's second law says that the total force on the mass must equal $ma$, where $m$ is the mass of the block and $a$ is that instantaneous acceleration; and this resultant force must be equal to the sum of all the forces acting on the block. 

Let $y(t)$ be the *position* of the block at time $t$ seconds as it bobs up and down. Then $ma$ equals $my''$. And this is equal to the sum of three other forces: 

- The force on the block due to gravity: $F_g = mg$ 
- The spring's restorative force: $F_s = -k(L_0 + y)$ Remember $L_0$ is the natural distance the spring is stretched by the block, and $y$ is the additional distance it's moved.
- The *damping force* that happens due to air resistance, friction, or some other outside influence. We usually assume that the damping force is proportional to velocity (higher velocity -> more damping) so this force is $F_d = -cy'$ where $c$ is a proportionality constant. 

Therefore: 

$$my'' = mg - k(L_0 + y) - cy'$$ 

Expand the right side to get $mg - kL_0 - ky - cy'$. Then notice that $mg - kL_0 = 0$, because when the spring is at rest, the force due to gravity has to cancel out the restorative force. So we have a simpler equation now:

$$my'' = - ky - cy'$$

Notice this is a **second order differential equation**. We could rewrite it further as: 

$$my'' + cy' + ky = 0$$ 

### Tasks 

1. Divide both sides by $m$ to get a second-order DE whose leading coefficient is $1$. 
2. Now suppose for the sake of argument that $c/m = 1$ and $k/m = 6$. Write the new DE. 
3. Use the trick from the Class Prep reading to convert this second-order DE into a system of two first-order DE's. (Summary: The trick is, let $u = y'$. Therefore $u' = y''$. Use this relationship to write a system involving $u$ and $y$.)
4. Go to the direction field tool from class and plot some solutions for this system. Time is considered nonnegative, so set your interval for $t$ to be something like $t = 0$ to $t = 10$ (you can choose different upper limits). What do you notice or wonder about the direction field plot? 
5. Switch over to a time plot. What do you notice or wonder? 
6. Take the resulting system and write it in matrix form. Use a computer to find the eigenvalues of the matrix. What do you notice or wonder? 