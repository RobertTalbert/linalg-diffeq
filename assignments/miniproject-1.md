# Miniproject 1

## Overview 

In this miniproject you will learn about *Markov chains* and use them to make predictions about long term trends in population growth and car ownership. 

**Prerequisites**: You'll need to know how to multiply a matrix times a vector, both by hand and using SymPy. 

**Initial deadline**: *Fill in here later*. This is the deadline for all *first* drafts of your solution. If you turn in a good-faith effort at a complete and correct solution by this date, you may continue to revise and resubmit as needed with no additional deadlines, until the final deadline of 11:59pm ET Sunday April 16. However, no *first* drafts will be accepted after the initial deadline. 

## Background

Complete the following before beginning this miniproject. These are not to be turned in! But you won't get far on the assignment without doing them. 

- Read Section 1.3.1 (Markov chains: An application of matrix-vector multiplication) on pages 26--28 in the textbook and work through the examples shown. 
- If needed, [watch the tutorial video where I walk through Example 1.3.3](https://gvsu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=97c3c6f8-d68e-461c-ac95-af72010dec46). This also shows how to use SymPy to do some of the math. 
- Practice with SymPy by using it to work Exercises 1-4 on page 29. 

## Assignment 

1. (Exercise 26) Suppose that for a large population that stays relatively constant (that is, there are no population explosions or mass migrations), people are classified as living in urban, suburban, or rural settings. Moreover, assume that the probabilities of the various possible transitions are given by the following rule: 

| Future location / current location | U (%) | S (%) | R (%) |
| ---------------------------------- | ----- | ----- | ----- |
| Urban                              | 92    | 3     | 2     |
| Suburban                           | 7     | 96    | 10    |
| Rural                              | 1     | 1     | 88    |

   (a) In plain English, what does the "10" in the table above mean? 
   (b) Let $U_n$, $S_n$, and $R_n$ represent the populations of people in urban, suburban, and rural areas respectively in year $n$ Write an equation that expresses $U_{n+1}$ in terms of $U_n$, $S_n$, and $R_n$. Then do the same for $S_{n+1}$ and $R_{n+1}$. 
   (c) Take the three equations from part (b) and convert them into a transition matrix $M$. Is this a stochastic matrix? Explain. 
   (d) Assume that the entire population is 250 million people, initially distributed into 100 million urban, 100 million suburban, and 50 million rural. With this assumption, predict the population distribution after 5, 10, and 25 years. 
   (e) As the number of years grows larger and larger, what appears to be happening to the population distribution? 

2. 

## Submission and Grading

Formatting
How to submit

Special items for grading 