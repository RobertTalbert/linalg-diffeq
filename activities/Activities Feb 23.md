# MTH 302: Linear Algebra and Differential Equations

## Activities for Thursday, February 23

>Parts marked **(AA5)** are to be written up individually and submitted in Application/Analysis 5, due Wednesday March 1. 

### Part 1: Separable DEs

1. Solve the following: 
   (a) $\frac{dy}{dx} = -2y^3$, $y(0) = 1$
   (b) $\frac{dy}{dt} = \frac{1+y^2}{2+3t}$, $y(-1/3) = 0$. 
2. A city has population $P$ (measured in thousands of people), in year $t$. The carrying capacity of the city (that is, the physical limit on the size of the city which the environment can support) is 100,000 people. The population grows according to the differential equation: 
$$\frac{dP}{dt} = -0.01P(P-100)$$
   (a) Make a slope field for this DE and look at the solution with the initial condition $P(0) = 20$. Describe the shape of the graph and the long-term value of the population. 

   (b) **(AA5)** Find a formula for the solution whose graph was in the slope field, i.e. the one with $P(0) = 20$. The integration technique involves *partial fractions*. You can do the partial fraction decomposition on a computer if you want. [Here is an example using Wolfram|Alpha](https://www.wolframalpha.com/input?i=partial+fractions+1%2F%28x*%28x-2%29%29). [Here is an example using the `apart` function in SymPy](https://github.com/RobertTalbert/linalg-diffeq/blob/main/tutorials/Partial_fractions_in_SymPy.ipynb). Do the integration step by hand, but any other math you need to do, you can use a computer. 

   (c) When you get a solution, plot it (in Desmos, for example) and compare it to the graphical solution from the direction field. They should look basically the same. If they don't, check your work in part (b). 

---

## Part 2: Separable + Exact DEs

Here are some initial value problems: 

1. $t^2 y' + y^2 = 1$, $y(2) = 0$ 
2. $e^{3t + y} \dfrac{dy}{dt} = 1$, $y(0) = 0$ 
3. $(2+t^2)y' + 2ty = 0$, $y(1) = 1$ 
4. $2x{y^2} + 4 = 2\left( {3 - {x^2}y} \right)y'$, $y\left( { - 1} \right) = 8$


- **(AA5)** Classify each as separable, exact, both (!), or neither and explain how you know. (If you think one of these is separable, the way you know is by actually separating the variables.)
- Solve as many of these as you have time for. Plot your solution and compare it to a slope field solution. 
