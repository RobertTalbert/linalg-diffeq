# MTH 302: Skill Quiz 10

This quiz contains the **third and final attempt** at Skill DE.3,  and the **second appearance** of Skill DE.4. 

**Instructions:**

* If you had a "Success" mark on a skill from the first quiz, **do not do the problem for that skill again**. You only need one "Success" on each skill, then you're done. 
* You should only be working on the skills that you **need** to work on (because you've never tried them, or you did and got "Retry") *and* you feel **ready** to work on. 
* Make sure to consult the [Standards for Student Work in MTH 302](https://github.com/RobertTalbert/linalg-diffeq/blob/main/course-docs/standards-for-student-work.md) document before starting on your work, so you're clear on what is expected and what constitutes a "successful" attempt. Also check the *Success criteria* below each problem. 
* As before, you may hand-write your work on paper, hand-write it in a notes app, or type it up. But **please start a new page for each Skill**. If a Skill takes more than one page, that's OK, but **don't put two skills on the same page.**
* When you are ready to submit your work: **Scan** your handwritten work to a clear, legible, black-and-white PDF using a scanner or scanning app -- **one PDF per problem**. So if you are doing both problems, you will have two PDFs: one for Skill LA.1 and another for Skill LA.2 (all parts).  
* Then, **upload each PDF to its designated folder** on Blackboard. For example the PDF for Skill LA.2 goes into the folder for Skill LA.2. **Please make sure you have put your work in the right folder, because work in the wrong folder significantly delays the grading process.**
* Make sure to **click "Submit"** after uploading each item, before exiting. 

---

## Foundational Skill DE.3

> **DE.3: I can generate a numerical solution to a first-order differential equation using Euler's method.**

Given the differential equation: 

$$\dfrac{dy}{dt} = -2ty^2$$ 

Consider the solution with $y(0) = 1$. Using a step size of $h = 0.1$, use Euler's method to estimate $y(0.1)$, $y(0.2)$, $y(0.3)$, $y(0.4)$, and $y(0.5)$. 

You must set up all calculations, and clearly show what you are doing. But you may carry out arithmetic calculations using a calculator. **Answers without corresponding calculations shown do not constitute acceptable work.** You **may not** use a spreadsheet on this problem. Carry all approximations out to six (6) decimal places. 

*Success criteria:* The algorithm for Euler's method must be correct. All computations must be clearly set up with all details present. Computations themselves must be correct, with **one** "simple" mistake allowed. (Note this is lower than the usual two "simple" mistakes allowed.) Decimal approximations must be to six decimal places; truncations to anything less than 6 places will be treated as a "simple" error or a non-simple error depending on the severity of the rounding. **Keep computations at six decimal places to avoid errors due to rounding.** For example, 3.141597 is an approximation to six decimal places; 3.14159 is not (that's five decimal places). 

---

## Foundational Skill DE.4

> **DE.4: I can solve a linear system of two differential equations.**

Consider the system of differential equations: 

$$\dfrac{dx}{dt} = -9x + 4y$$

$$\dfrac{dy}{dt} = -6x + y$$

(a) Find the straight-line solutions for the system. 

(b) State the general solution for the system. 

(b) Find the particular solution satisfying $x(0) = 4, y(0) = -2$. 

You may use a computer to do basic arithmetic and eigenvalue/eigenvector computations without needing to show work. All other work must be shown in detail. 

*Success criteria*: The general solution is completely correct. The particular solution is correct with up to two simple errors allowed. All work other than basic arithmetic and eigenvalue/eigenvector computations is shown in detail – this includes any matrix row reduction steps. Producing a row-reduced matrix without all intermediate steps shown will result in a "Retry". 