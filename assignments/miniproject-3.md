---
class: mth302
---

# Miniproject 3

**Initial due date: Sunday, xxx at 11:59pm ET**

## Overview 

In this miniproject, you'll apply concepts from linear algebra to study **discrete dynamical systems**. These are related to the idea of *Markov chains* that was the subject of Miniproject 1 and are the linear algebra analogue of systems of differential equations which we will study later. 

**Prerequisites:** You'll need to know what an eigenvalue and eigenvector for a matrix are, and how to find these using SymPy. This miniproject also requires some knowledge of matrix-vector multiplication. 

## Background

Complete the following before beginning this miniproject. These are not part of your writeup, but you'll need the knowledge before you can understand the tasks in the assignment. 

- If you are unsure how to use SymPy to find eigenvectors and eigenvalues of a matrix, [read the tutorial](https://docs.google.com/presentation/d/18qj8SgWcN6GzVlPgvNGiC4VSRvOFqYOAHWQZvTnNfXA/edit?usp=sharing) and work with some of your own examples. For example, take some matrices whose eigenvavlues and eigenvectors we have found in class work, and redo these using SymPy. 
- It's highly recommended that you read Example 1.3.1 in the text and look at the video walkthrough on Blackboard (Blackboard > Tutorials > Math Examples). This was posted for Miniproject 1 but this Miniproject uses the ideas here. 
- Read through the brief text on page 123 of the text, starting at "1.13.3 Discrete dynamical systems". It's just one paragraph, then the exercises begin. Again, if you are unfamiliar with Markov chains, see the previous bullet point. 

## Assignment 

*Some notes on these exercises appear below.* 

1. Complete part (a) of the exercises in 1.13.3. 
2. Complete part (b) of the exercises in 1.13.3. 
3. Complete part (c) of the exercises in 1.13.3. Note that this part asks three questions that involve numbers but which also require verbal explanations. Make sure your responses are in complete, coherent English sentences that explain everything -- don't just give answers, but explain how you arrived at your answers and why your answer is correct. 
4. Complete part (d) of the exercises in 1.13.3. Do your work in SymPy and be sure your code is correct. Be sure as well to answer the question in this part, which asks for a convincing argument that uses not only the computation but also the response to (b). Make sure your responses are in complete, coherent English sentences that explain everything -- don't just give answers, but explain how you arrived at your answers and why your answer is correct. 
5. Finally complete part (e) of the exercises in 1.13.3. This part requires experimentation, which you should summarize in your writeup, and an answer to a question. Make sure your responses are in complete, coherent English sentences that explain everything -- don't just give answers, but explain how you arrived at your answers and why your answer is correct. 

## Notes on this Miniproject

- Part (a) asks you to think about the eigenvalues and eigenvectors of an $n \times n$ matrix, $A$. It asks you to assume that $A$ has "$n$ real linearly independent eigenvectors". This means: (1) $A$ has the same number of eigenvectors as there are rows/columns; (2) all of those eigenvectors contain only real-number entries, not complex numbers; and (3) the eigenvectors are linearly independent. For example, check that the matrix

$$\begin{bmatrix} 1 & 0 \\ 2 & 1 \end{bmatrix}$$

does not have two linearly independent eigenvectors. The only eigenvectors you will find for this one are $[0,1]^T$ and multiples of this. 

- Also in part (a), there is an inequality given. This is just asking you to take the eigenvalues of $A$ and put their absolute values in order with $\lambda_1$ being the one that has the largest magnitude. This is sometimes called the *dominant eigenvalue* for reasons you'll see in this exercise. For example if 
$$A = \left[\begin{matrix}- \frac{8}{5} & - \frac{18}{5}\\- \frac{12}{5} & - \frac{2}{5}\end{matrix}\right]$$
then the eigenvalues are $-4$ and $2$. Since $|-4| > |2|$ we would have $\lambda_1 = -4$ and $\lambda_2 = 2$. 

- In part (a) again, you're asked to explain why an equation with $\mathbf{x}_0$ on the left is true. Hint: Remember we are assuming that there are $n$ linearly independent eigenvectors. 

- Also in part (a), a fact about matrix-vector multiplication is that matrix multiplication distributes over vector addition. So if $\mathbf{a}, \mathbf{b}$ are vectors and $A$ is a matrix then $A(\mathbf{a} + \mathbf{b}) = A \mathbf{a} + A\mathbf{b}$. (This is all assuming that the operations are defined.) You can use that fact in the second equation to explain. 




## Submission and Grading

### Formatting and special items for grading

Please review the section on Miniprojects in the document [Standards For Student Work in MTH 302](https://github.com/RobertTalbert/linalg-diffeq/blob/main/course-docs/standards-for-student-work.md#standards-for-miniprojects) before attempting to write up your submission. Note that *all* Miniprojects: 

- **Must be typewritten**. If any portion of the submission has handwritten work or drawings, it will be marked *Incomplete* and returned without further comment. 
- **Must represent a good-faith effort at a complete, correct, clearly communicated, and professionally presented solution.** Omissions, partial work, work that is poorly organized or sloppily presented, or work that has numerous errors will be marked *Incomplete* and returned without further comment. 
- **Must include clear verbal explanations of your work when indicated, not just math or code**. You can tell when verbal explanations are required because the problems say something like "Explain your reasoning". 

Your work here is being evaluated *partially* on whether your math and code are correct; but just as much on whether your reasoning is correct and clearly expressed. Make sure to pay close attention to both. 

Miniproject 3 **must be done in a Jupyter notebook using SymPy to carry out all mathematical calculations**. [A sample notebook, demonstrating the solution to a Calculus problem, can be found here](https://github.com/RobertTalbert/linalg-diffeq/blob/main/tutorials/Example_of_solution_in_a_notebook.ipynb). Study this first before writing up your work. 


### How to submit

You will submit your work on Blackboard in the *Miniproject 3* folder under *Assignments > Miniprojects*. But you will *not* upload a PDF for Miniprojects. Instead you will **share a link that allows me (Talbert) to comment on your work**. [As explained in one of the Jupyter and Colab tutorials](https://gvsu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ef5c0e24-5c1d-437f-be05-af730108b6d8), the process goes like this: 

1. In the notebook, click "Share" in the upper right. 
2. **Do not share with me by entering my email.** Instead, go to *General Access*, and in the pulldown menu select "Anyone with the link", then set the permissions to "Commenter". 
3. Then click "Copy Link". 
4. **On Blackboard**, go to the *Assignments* area, then *Miniprojects*. Select Miniproject 3. 
5. Under **Assignment Submission**, where it says *Text Submission*, click "Write Submission".  
6. **Paste the link to your notebook in the text area that appears.** 
7. Then click "Submit" to submit your work. 

I will then evaluate your work using the link. Specific comments will be left on the notebook itself. General comments will be left on Blackboard. 