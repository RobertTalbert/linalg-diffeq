# MTH 302: Linear algebra and differential equations

## Activities for Tuesday, February 21

### Activity 1: Population growth 

When GVSU opened in 1963, it enrolled 224 students. Since then the enrollment of the university has exploded, reaching a peak of 25,460 students in 2016 (it's 21,648 as of Fall 2022). (Source: https://www.gvsu.edu/ia/history-of-enrollment-degrees-awarded-7.htm)

Let's model GVSU's enrollment using differential equations. 

1. Start by assuming that enrollment growth was unrestricted in the early years. (This is a big assumption, but we make these when building models.) That means that **the rate of growth in the enrollment is proportional to the size of the enrollment**. If $E$ is the enrollment of the university in year $t$ (with $t=0$ corresponding to 1963), write a differential equation that expresses this statement in mathematical terms. 
2. **(AA)** Solve the initial value problem using the DE you just set up and the initial condition $E(0) = 224$. There is a proportionality constant in the differential equation; how will you find its value here? 
3. **(AA)** What does the DE predict for the enrollment in year $t=10$, which is 1973? 
4. **(AA)** The actual enrollment in year $t = 10$ was 5,920 students. What's the percentage error in your prediction? You can find the percent error using the formula $\left| \dfrac{v_A - v_E}{v_E}\right| \cdot 100\%$ where $v_A$ is the actual value of enrollment and $v_E$ is the estimated or expected value of enrollment. 
5. **(AA)** Repeat questions 3 and 4 for the years $t=20, 30, 40$ and $50$. Is the percent error getting better, getting worse, or staying basically the same over longer periods of time? What does this suggest about your model? 
6. Look at a graph of the solution to the IVP in question 2 and compare it to a scatterplot of the actual population data. How accurate would you say the model is? What could you do to improve its accuracy? 



### Activity 2: Logistic growth

This activity will set you up to work on one of the upcoming Miniprojects on differential equations. 

The assumption that a population grows without restrictions is big, and often unrealistic. So here's an addition we can make to our modeling toolbox that makes population modeling a little more plausible. 

Real populations tend to behave like unrestricted growth as long as the size of the population is relatively small. But as the populations grow, they tend to level off at a certain level we'll denote by $K$. This value is called the *carrying capacity* of the population and represents the physical limit of the population size, beyond which the environment can no longer support the population. 

If we introduce a carrying capacity into a population model, we have these assumptions. We let $P$ be the size of the population at time $t$. 

* For small values of $P$, the rate of growth in $P$ is proportional to $P$. 
* If $P$ is close to, but less than $K$. then the rate of growth in $P$ will be positive but small; and the closer $P$ gets to $K$ the closer the rate of change in $P$ gets to zero. 
* If $P$ is close to, but greater than $K$. then the rate of growth in $P$ will be negative but small; and the closer $P$ gets to $K$ the closer the rate of change in $P$ gets to zero. 

1. Looking at a scatterplot of the GVSU enrollment data, make a reasonable guess at a carrying capacity for GVSU's enrollment. (It will not be perfect; remember *all models are wrong, but some are useful*.)
2. Consider the differential equation: $\displaystyle{\frac{dP}{dt} = kP\left( 1 - \frac{P}{K}\right)}$ where $K$ is the carrying capacity you found. Explain in words why this differential equation satisfies all three of the assumptions we listed. 
3. Generate a slope field for your model and look at it. Use the proportionality constant $k$ that you found in the first activity and the carrying capacity that you just estimated. What do you notice or wonder about? 
4. We don't know how to solve this DE algebraically yet (that's coming on Thursday) but we can ask SymPy to do so. Using your value of the carrying capacity, find an algebraic formula for $P(t)$ using SymPy. (Reminder: There is a [tutorial](https://github.com/RobertTalbert/linalg-diffeq/blob/main/tutorials/Solving_DEs_algebraically_in_SymPy.ipynb) on how to do this.)
5. Take your formula and plug in $t = 0, 10, 20, 30, 40, 50$, and $60$. The first six of these are year values for which we have the actual enrollment data; how accurate is the new model compared to the previous one in the first activity? The last one $t = 60$ is a predicted enrollment for Fall 2023. What is that predicted enrollment? 



### Activity 3: Mixing things up  

This activity is a little like the one from your textbook that was used to set up the topic of differential equations, but with a twist. 

Suppose a tank contains 350 liters of liquid with 9 grams of salt. A mixture containing 7 grams per liter is pumped into the tank at a rate of 3 liters per minute. The mixture is well-mixed in the tank, then pumped out at a rate of 3 liters per minute. Let $A(t)$ be the amount of salt in grams, in the tank at time $t$ minutes. 

1. Set up an initial value problem that relates the rate of change in the amount of salt, to the amount of salt in the tank at time $t$. You need both a differential equation and an initial value. 

2. The IVP you set up should involve a linear but non-homogeneous differential equation. Set up the solution for the differential equation, which will involve an integral and an integrating factor. Don't actually find the solution, though (unless you have time and want the practice). 

3. Solve the IVP you set up, using SymPy. 

4. This IVP wasn't too hard because the rate at which liquid is being pumped in is the same rate it's being pumped out: 3 liters per minute. But what if the liquid were being pumped out faster than it's being pumped in? Visually, you would see the liquid level in the tank decreasing over time until the tank is empty. Let's modify the IVP with this new assumption. 

   (a) We still have the same concentration of salt coming into the tank, but since the volume of the tank is decreasing over time now, the expression for the concentration of salt in the tank has to change. What is the concentration of salt, in liters per minute, at time $t$ minutes? 

   (b) Modify the differential equation using this new concentration term, then solve the corresponding IVP with SymPy. 