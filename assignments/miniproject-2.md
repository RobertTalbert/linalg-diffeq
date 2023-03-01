---
tags: mth302
---

# Miniproject 2

**Initial due date: Sunday, February 26 at 11:59pm ET**

## Overview 

In this miniproject, you'll explore the concept of *matrix transformations* and use matrix transformations in $\mathbb{R}^3$ to create a very simple computer animation --- and see how linear algebra is used to make more complex animations happen. 

**Prerequisites:** You'll need to know how to multiply a $3 \times 3$ matrix to a $3 \times 1$ vector using SymPy, as well as what some of our recent theorems about matrices and invertibility say. Also, you'll need to do a bit of background learning using the video mentioned below. 

## Background

Complete the following before beginning this miniproject. These are not part of your writeup, but you'll need the knowledge before you can understand the tasks in the assignment. 

* Watch the video tutorial "Matrix transformations" posted to *Blackboard > Tutorials > Math Examples* at the top of the list. [Here is a direct link](https://gvsu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=3b4e78b2-b2fd-4842-a855-afa400fb183a) if you prefer not to go through Blackboard. 
* Read the tutorial "Defining symbolic variables in SymPy" posted to *Blackboard > Tutorials > SymPy tutorials* at the bottom of the list. [Here is a direct link](https://github.com/RobertTalbert/linalg-diffeq/blob/main/tutorials/Defining_symbolic_variables_in_SymPy.ipynb) if you prefer not to go through Blackboard. 
* [Click here to go to a section of an online text](https://davidaustinm.github.io/ula/sec-transforms-geom.html) used in other linear algebra courses at GVSU. To check your understanding of matrix transformations and composition, work through the Preview Activity at the beginning. Answers are below. 
* Then in that same section, go to *Section 2.6.2: Matrix transformations and computer animation*. Read through all the text up to Activity 2.6.4. Most of the tasks in this Miniproject are in that Activity. 

**Answers to the Preview Activity**: (a) $[2,-4]^T$; (b) $[x, -y]^T$; (c) $[1,0]^T$ and $[0,-1]^T$; (d) $A = \begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix}$; (e) $T \circ T$ is the the "identity" transformation that keeps each vector the same because $(T \circ T)(x) = \begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix} \begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix} \mathbf{x} = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} \mathbf{x} = \mathbf{x}$. 

## Assignment 

1. Do part (a) of Activity 2.6.4. Do the matrix-vector multplication that's indicated, using SymPy and eight symbolic variables (there are six of these in the matrix and two in the vector). 
2. Do part (b) of Activity 2.6.4. You can find the matrix involved in the transformation by trial and error using the sliders. Then, in SymPy, multiply this matrix to the vector $[x,y,1]^T$ and explain why the resulting vector has been correctly transformed. 
3.  Do part (c) of Activity 2.6.4. You can find the matrix involved in the transformation by trial and error using the sliders. Then, in SymPy, multiply this matrix to the vector $[x,y,1]^T$ and explain why the resulting vector has been correctly transformed. 
4.  Do part (d) of Activity 2.6.4. There are four matrices to find this time. You can find them by trial and error using the sliders. Then, in SymPy, multiply each matrix to the vector $[x,y,1]^T$ and explain why the resulting vector has been correctly transformed. 
5. Do part (e) of Activity 2.6.4. There are two matrices to find. You can find the two matrices by trial and error using the sliders. Then, in SymPy, multiply each matrix to the vector $[x,y,1]^T$ and explain why the resulting vector has been correctly transformed. 
6. Do part (f) of Activity 2.6.4. There are three matrices to find. You can find the two matrices by trial and error using the sliders. Then, in SymPy, multiply each matrix to the vector $[x,y,1]^T$ and explain why the resulting vector has been correctly transformed. 
7. Do part (g) of Activity 2.6.4. 
8. All of the matrices in the transformations used in these activities have the form $\left[\begin{array}{rrr} a & b & c \\ d & e & f \\ 0 & 0 & 1 \\ \end{array}\right]$ . Notice that the third column of this matrix can't ever be a linear combination of the first two, because linearly combining the first two always leaves a $0$ in the third component. Therefore the columns of this matrix are linearly independent, *except* when the second column is a scalar multiple of the first one. Give an example where this happens; then go back to the interactive pictures in the text and enter those matrix entries using the sliders and observe the effect. If the columns of this matrix are linearly dependent, what happens to the image we're animating? 
9. Also notice that if the columns of the matrix from question 8 are linearly dependent, then the Invertible Matrix Theorem would say that the matrix is not invertible. Why does this make sense given the effect that the matrix from question 8 has on the image? (That is, explain why can't we invert the transformation in this case, using only visual descriptions.) 


## Submission and Grading

### Formatting and special items for grading

Please review the section on Miniprojects in the document [Standards For Student Work in MTH 302](https://github.com/RobertTalbert/linalg-diffeq/blob/main/course-docs/standards-for-student-work.md#standards-for-miniprojects) before attempting to write up your submission. Note that *all* Miniprojects: 

- **Must be typewritten**. If any portion of the submission has handwritten work or drawings, it will be marked *Incomplete* and returned without further comment. 
- **Must represent a good-faith effort at a complete, correct, clearly communicated, and professionally presented solution.** Omissions, partial work, work that is poorly organized or sloppily presented, or work that has numerous errors will be marked *Incomplete* and returned without further comment. 
- **Must include clear verbal explanations of your work when indicated, not just math or code**. You can tell when verbal explanations are required because the problems say something like "Explain your reasoning". 

Your work here is being evaluated *partially* on whether your math and code are correct; but just as much on whether your reasoning is correct and clearly expressed. Make sure to pay close attention to both. 

Miniproject 2 **must be done in a Jupyter notebook using SymPy to carry out all mathematical calculations**. [A sample notebook, demonstrating the solution to a Calculus problem, can be found here](https://github.com/RobertTalbert/linalg-diffeq/blob/main/tutorials/Example_of_solution_in_a_notebook.ipynb). Study this first before writing up your work. 


### How to submit

You will submit your work on Blackboard in the *Miniproject 2* folder under *Assignments > Miniprojects*. But you will *not* upload a PDF for Miniprojects. Instead you will **share a link that allows me (Talbert) to comment on your work**. [As explained in one of the Jupyter and Colab tutorials](https://gvsu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ef5c0e24-5c1d-437f-be05-af730108b6d8), the process goes like this: 

1. In the notebook, click "Share" in the upper right. 
2. **Do not share with me by entering my email.** Instead, go to *General Access*, and in the pulldown menu select "Anyone with the link", then set the permissions to "Commenter". 
3. Then click "Copy Link". 
4. **On Blackboard**, go to the *Assignments* area, then *Miniprojects*. Select Miniproject 2. 
5. Under **Assignment Submission**, where it says *Text Submission*, click "Write Submission".  
6. **Paste the link to your notebook in the text area that appears.** 
7. Then click "Submit" to submit your work. 

I will then evaluate your work using the link. Specific comments will be left on the notebook itself. General comments will be left on Blackboard. 