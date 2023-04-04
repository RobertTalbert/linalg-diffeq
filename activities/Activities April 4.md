# MTH 302: Linear Algebra and Differential Equations

## Application 1: Modeling a mixing problem with two tanks

Two tanks, labelled Tank A and Tank B, contain a saltwater solution. The volumes of Tank A and B are 200 and 400 liters respectively and are completely full. Each tank has a pipe pumping water into the tank, and as water comes into each tank, it's mixed in with the salt water that was already present. Each tank also has a drain that removes excess solution, and a pipe that connects and moves the solution from one tank to the other. 

![Double mixing problem diagram](C:\Users\talbertr\Desktop\Double mixing problem diagram.png)

Assume that all of the inflows and outflows to and from these tanks occur at a rate of 5 liters per minute. This keeps the volume of each tank constant. **How much salt is in each tank at any given moment in time?** 

Answering this question requires a *system* of differential equations since each tank's salt content is changing, not only because of the water coming in and out but also because of the other tank's contents coming in and out. Let $x_A$ be the amount of salt (in grams) in tank A at time $t$ minutes, and let $x_B$ be the amount of salt in tank B at $t$ minutes. 

1. Assume that the water flowing into tank A is contaminated with 4g of salt per liter. How much salt is coming into tank A each minute from the "Inflow to A" pipe? 
2. How much salt (in grams) is leaving the drain from A (seen on the left side of the diagram above) each minute? How much salt is leaving tank A through the "A to B pipe"? 
3. How much salt *in total* is leaving tank A each minute? 
4. How much salt (in grams) is coming in to tank A from tank B each minute? 
5. Use the information from the first four questions to set up a differential equation for the rate of change in the amount salt in tank A per unit time. It should look like this, with the right-hand side filled in. Note: you should see both $x_A$ and $x_B$ on the right. 

$$\dfrac{dx_A}{dt} = \underline{\hspace{2in}}$$

6. Assume that the water flowing in to tank B is contaminated with 7g of salt per liter. How much salt is coming into tank B through the "Inflow to B" pipe? 
7. How much salt is leaving tank B *in total* each minute? (Compare with questions 2 and 3 above.)
8. How much salt is coming into tank B from tank A each minute? 
9. Set up a second differential equation: 

$$\dfrac{dx_B}{dt} = \underline{\hspace{2in}}$$

10. Take the system you have set up and produce a phase portrait using the direction field tool. Suggestion: Use $x$ for $x_A$ and $y$ for $x_B$, then set the window so that $0 \leq x,y \leq 3000$. Plot a few particular solutions. What do you notice or wonder about? 
11. Is there am equilibrium state for this system, where the amount of salt in each tank will never change? If so, what is it? 
12. *Challenge:* Find an algebraic solution for the system. 

---

## Application 2: Spring-mass systems 

Spring-mass systems like the one shown above are very common in many applications. As the mass moves, $y(t)$ denotes its displacement from its equilibrium position over time. Here is a fun interactive demo you can play with to visualize what's happening: https://phet.colorado.edu/sims/html/masses-and-springs/latest/masses-and-springs_en.html 

Let's build a model for $y(t)$ using basic physics and our knowledge of differential equations. 

1. Newton's Second Law says that force is equal to mass times acceleration ($F = ma$). Here, acceleration is *not* acceleration due to gravity but the acceleration of the mass as it moves. Rewrite the equation $F = ma$ with $a$ replaced by an appropriate expression involving $y$ that gives the mass' acceleration. 

2. As the mass moves, there is a second force acting on it, the *restorative force* of the spring. Hooke's Law says that this restorative force, $F_s$, is proportional to the displacement and is directed toward the rest position. In math terms, $F_s = -ky$ where $k$ is the "spring constant" that quantifies the stiffness of the spring. The negative sign indicates the direction of the force. Assuming the two forces mentioned here -- the restorative force from the spring and the force due to acceleration -- are equal, write a differential equation that expresses the situation. 

   **Stop here for a debrief** 

3. Consider the function $y(t) = \cos(\beta t)$. Under what conditions on $\beta$ is $y(t)$ a solution to the differential equation? 

4. If $y(t) = \cos(\beta t)$ then in visual terms, the mass would just oscillate up and down forever with a regular period. In terms of $k$ and $m$, what is that period? 

5. Rewrite the differential equation as a system of two first-order equations

6. Suppose a mass weighing 4 pounds stretches a spring 4 inches. Formulate an initial value problem that corresponds to the motion of this mass-spring system, if the mass is extended 1 foot (12 inches) from its rest position and then released (with no initial velocity). Note: "4 pounds" is a measure of *force* not a measure of mass. Use this to calculate the spring constant. The spring constant is always taken to be positive. Also note: An object that weighs 4 pounds has a mass of about 1.8kg if it's near the Earth's surface. 

7. Create a graph of the solution to the previous initial-value problem using our slope field tool. Also use the tool to make a time plot of the solution. 

8. Solve that initial-value problem algebraically. 