# MTH 302: Linear Algebra and Differential Equations

Parts of these activities will be assigned to Application/Analysis 10. Those parts will be announced later. 

## 1: Solving a second-order equation

1. Go back to the Class Prep and consider $$y'' - y' - 12y = 0$$. 

   (a) Make the guess $y = e^{rt}$ for a solution. Find $y'$ and $y''$ and then substitute into the left side. 

   (b) Find the values of $r$ that solve the equation. (There will be two of them.) 

   (c) Replace those values of $r$ back into the guess $y = e^{rt}$. Then check that both functions individually solve the differential equation. 

   (d) Form a linear combination of those two functions using arbitrary constants $c_1$ and $c_2$ as weights, and check that the linear combination is also a solution to the DE. 

2. Mimic this process to find the general solution to each of the following second-order DEs. Each group will be responsible for one of these and putting the work on the board. But do more for practice. 

   (a) $y''+ y' - 2y = 0$

   (b) $y'' - y = 0$

   (c) $y''+ 3y' = 0$

   (d) $y'' = 0$

   (e) $y'' + 4y' + 3y = 0$

   (f) $y'' + y' - y = 0$ 

## 2: Application to spring-mass systems 

In a spring-mass system, the displacement $y(t)$ of the mass from its natural equilibrium is governed by the equation 

$$y'' + \dfrac{c}{m}y' + \dfrac{k}{m}y = \dfrac{1}{m}F(t)$$ 

where $c$ is a damping constant (coming from friction within the system), $k$ is the spring constant, $m$ is the mass of the suspended object, and $F$ is a forcing function (some force from outside the system acting upon it). 

For an *unforced* system with $c=3$, $k=2$, and $m=1$, determine the displacement of the mass at time $t$ is the system is set in motion with initial displacement $y(0) = 2$ and initial velocity $y'(0) = 1$. 

## 3: What if the roots aren't real numbers? 

Solve the second-order DE: 

$$y'' + 2y' + 10y = 0$$ 

using the method you've learned. 

1. Set up and solve the characteristic equation. What's different this time? 
2. Let $r$ be one of the characteristic roots. Go ahead and set up $y = e^{rt}$ as a solution, as usual. Then simplify this using Euler's formula. 
3. The result of the previous part will give you *two* functions: One attached to the real part, and a second attached to the imaginary part. Check that *both* of these solve the original DE. 
4. Using the results of the previous question, state the general solution to the DE. 