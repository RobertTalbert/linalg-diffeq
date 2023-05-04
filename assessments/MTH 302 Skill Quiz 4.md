# MTH 302: Skill Quiz 4

This quiz contains the **second attempt** at Skill LA.3 and the **first attempt** at Skills LA.4 and LA.5. 

**Instructions:**

* If you had a "Success" mark on a skill from the first quiz, **do not do the problem for that skill again**. You only need one "Success" on each skill, then you're done. 
* You should only be working on the skills that you **need** to work on (because you've never tried them, or you did and got "Retry") *and* you feel **ready** to work on. 
* Make sure to consult the [Standards for Student Work in MTH 302](https://github.com/RobertTalbert/linalg-diffeq/blob/main/course-docs/standards-for-student-work.md) document before starting on your work, so you're clear on what is expected and what constitutes a "successful" attempt. Also check the *Success criteria* below each problem. 
* This week's quiz is done entirely asynchronously since we are not meeting as a class. Please submit your work on Blackboard by **11:59pm ET Monday, January 30**.
* As before, you may hand-write your work on paper, hand-write it in a notes app, or type it up. But **please start a new page for each Skill**. If a Skill takes more than one page, that's OK, but **don't put two skills on the same page.**
* When you are ready to submit your work: **Scan** your handwritten work to a clear, legible, black-and-white PDF using a scanner or scanning app -- **one PDF per problem**. So if you are doing both problems, you will have two PDFs: one for Skill LA.1 and another for Skill LA.2 (all parts).  
* Then, **upload each PDF to its designated folder** on Blackboard. For example the PDF for Skill LA.2 goes into the folder for Skill LA.2. **Please make sure you have put your work in the right folder, because work in the wrong folder significantly delays the grading process.**
* Make sure to **click "Submit"** after uploading each item, before exiting. 

---

## Foundational Skill LA.3

> **LA.3: I can determine if a collection of vectors is linearly independent.**

Below are three sets of vectors. For each, determine if the set is linearly independent or linearly dependent. And for each, state the answer ("linearly independent" or "linearly dependent") clearly, and give a 1-2 sentence explanation for why your answer is correct based on calculations or other evidence about the vectors. *You are allowed to use a computer or calculator to do any basic arithmetic and any row-reduction steps*. 

1. $[1,5,2]^T$ and $[2,-5,4]^T$ in $\mathbb{R}^3$ 
2. $[3,4]^T, [4,5]^T$, and $[5,6]^T$ in $\mathbb{R}^2$ 
3. $\left[\begin{matrix}2\\7\\-5\\5\end{matrix}\right]$ , $\left[\begin{matrix}10\\-2\\4\\9\end{matrix}\right]$, and $\left[\begin{matrix}-4\\-8\\2\\0\end{matrix}\right]$ in $\mathbb{R}^4$ 

*Success criteria:* Appropriate concepts from linear algebra are used correctly to find the answers on each. The setup and steps (except for basic arithmetic and row-reduction steps) for all calculations are clearly indicated. The answer on each part ("linearly independent" or "linearly dependent") is consistent with the results of computations. Each item has not only an answer but also a clear one- to two-sentence explanation in English that correctly explains why the answer is correct. **The results of all RREF computations must be correct**.

---

## Foundational Skill LA.4

> **LA.4: I can add, subtract, and multiply matrices.**

Let $A$, $B$, and $C$ be the given matrices. In each of the parts, compute (by hand) the prescribed algebraic combination of $A$, $B$, and $C$ whenever the operation is defined. If the operation is not defined, say so and explain why. 

$$A = \begin{bmatrix} -6 & 3 \\ 0 & 2 \\ -3 & -4 \end{bmatrix} \quad B = \begin{bmatrix} -5 & 3 \\ 2 & 4 \end{bmatrix} \quad C = \begin{bmatrix} 1 & 0 \\-5 & 3 \end{bmatrix} $$

(a) $-3B + 4C$ 

(b) $A + B$ 

(c) $AB$ 

(d) $CA$ 

(e) $A^TC$ 

*Success criteria*: All parts that are not defined are clearly indicated as such and a correct explanation is given on each. All parts that are defined, have correct answers with the exception of two "simple" errors allowed overall. (A "simple" error is one that does not pertain to the concept being assessed and which does not oversimplify the problem.) **No technology is allowed on this problem.** 

---

## Foundational Skill LA.5

>  **LA.5: I can determine if a matrix is invertible, using information about the matrix.**

For each of the matrices below, determine whether the matrix is invertible using no further computation. (For example you may not type the matrix in to SymPy and have it find the inverse.) State clearly whether or not the matrix is invertible, and give an explanation for your reasoning.  If there is not enough information to determine whether the matrix is invertible, say so and then explain why.

1. $A$ is a $4 \times 4$ matrix that row-reduces to $\begin{bmatrix} 1 & 0 & 0 & 0 \\ 0 & 1 & 0 & 0 \\ 0 & 0 & 1 & 0 \\ 0 & 0 & 0 & 1  \end{bmatrix}$ 
2. $B$ is a $3 \times 3$ matrix and the span of its columns is the plane $x+y+z = 1$ in $\mathbb{R}^3$ 
3. $C$ is a $15 \times 15$ matrix whose determinant is $-1$ 

*Success criteria*: Each part has a correct answer (is invertible, is not invertible, or not enough information) along with a correct explanation for the answer. 