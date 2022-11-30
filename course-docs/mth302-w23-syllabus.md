# MTH 302: Linear Algebra and Differential Equations

(insert graphic here)

> All models are wrong, but some are useful. 
> 

## About MTH 302 and this syllabus

**Welcome to MTH 302!** I'm Dr. Robert Talbert, the professor of this course. I'm grateful you're here, and I think you're going to love what you learn this semester. 

MTH 302 about **modeling and understanding systems undergoing change.** A car driving down a bumpy road is such a system, as it its shock absorbers encounter and smooth out the bumps. So is an ecosystem where one species preys upon another and the populations change dynamically. So is an electric circuit with a resistor and power supply; or two guitar strings vibrating next to each other at different frequencies; and many other systems we encounter every day. 

In MTH 302 we model and understand these systems using two fundamental tools: 

- **Linear algebra**, the study of systems of linear equations and their solutions; and 
- **Differential equations**, which studies equations that connect the current state of a quantity to its rates of change. 

Both tool sets are foundational in their own right; but as we will see, they can also mutually support each other in interesting and useful ways. 

**This syllabus contains all the information you need to navigate the course.** The main document will be kept continuously up to date at this link. When you see blue- or purple-underlined text in the syllabus or any other document, it's a clickable link. For example, [click here for a cat video](https://www.youtube.com/watch?v=aFuUidBR1aQ). A PDF version of the syllabus will also be available on Blackboard in the *Syllabus and Calendar* area, but it will not be updated unless there is a major change. 

**This document is meant to be read once, then searched as needed.** If you need to find something, the easiest way is to pull up the document, hit `Control-F` and then do a search for the text you're looking for. 

All course materials for MTH 302 are available on GitHub at https://github.com/RobertTalbert/linalg-diffeq. 

## Course information 

- **Class meetings:** Section 03 meets TR 2:00-3:50 in EC 421. Section 04 meets TR 4:00-5:50 in EC 710. 
- **Instructor:** Robert Talbert, Ph.D., Professor of Mathematics. 
- **Office location:** MAK C-2-513, but I will be using **INSERT PERCHING OFFICE HERE**. 
- **Drop-in hours:** 3:00-5:00pm in Mackinac Hall C-2-513. Online visits are available by appointment at https://calendly.com/robert-talbert/online-drop-in-meeting.  
- **Appointments outside drop-in hours:** Available on a limited basis. Go to https://calendly.com/robert-talbert, choose a meeting type, then choose an open 20-minute time slot. 
- **Contacting the prof:** Email (talbertr@gvsu.edu) is preferred. Be sure to read my availability/response policy.  **INSERT LINK**
- **Course calendar:** The official course calendar is in Appendix B and on Blackboard. *In case of a date conflict on assignments or course documents, the Class Calendar is assumed to be correct.* 
- **Definition of "week":** In our course, a "week" is defined to begin at 12:01am ET on *Monday* and end at 11:59pm ET the following *Sunday*. 
- **Blackboard and announcements:** Our Blackboard page is at https://lms.gvsu.edu. Announcements will be posted on Sundays, with occasional mid-week announcements. *Be sure to check announcements, email, and the calendar at least once daily.*
- **Textbook:** *Differential Equations with Linear Algebra* by Boelkins, Goldberg, and Potter. It is freely available online through the GVSU Library; [click here to access](https://ebookcentral-proquest-com.ezproxy.gvsu.edu/lib/GVSU/detail.action?docID=472100). **I recommend you download individual PDFs of the chapters so you can use them offline.** We will be working through most of Chapters 1--5. 

**Course tools:** We will use computer tools extensively in the course. In addition to Blackboard, these include: 

- **Perusall** (http://perusall.com): An online tool for collaborative reading and viewing. 
- **Python**: A widely-used and easy to learn programming environment. We will not be doing much actual programming in the course, but instead using two packages for doing math: **SymPy** (a package for doing symbolic math) and **NumPy** (for numerical analysis). 
- **Jupyter notebooks** via **Google Colab** (http://colab.research.google.com): Jupyter is an open-source graphical notebook interface for working with Python. Colab is a Google product for working with Jupyter notebooks, that lives in the cloud and can be connected to your GVSU Google Drive. 
- **Miro** (http://miro.com): An online whiteboard tool for presentations and collaborative work. We'll use it in class from time to time. 

We'll get fluent with all of these tools during the first week of class using some custom tutorial videos I have made. 

## How to succeed in MTH 302 

**My top prority as a professor at GVSU is your success**. In MTH 302, you can expect:

- A learning environment that challenges you, but also where support is readily available and freely given. This class is *a safe space to make mistakes*. 
- Work that is meaningful and not "busy work", and grading practices that prioritize growth and improvement. 
- Transparency and openness in how the course is run, including clear instructions on what you need to do and when. 
- Openness to your ideas about the course, with regular solicitations for feedback that are taken seriously through a continuous improvement process. 
- Above all, **respect** -- for you as a learner, as an adult, and as a human. 

On your end, your success in the course depends on three things: 

1. **Active engagement during class time**. All the available research on learning says that the best way to learn is to be an active participant in the process. Students who approach the class with a passive mindset typically struggle, and often fail. Those who approach it with an active mindset, on the other hand, often surprise themselves with how much and how well they learn. Make it a priority not to just attend and take notes, but *get involved*. 
2. **Asking questions**. The material in MTH 302 can be challenging, and it is 100% certain you will be lost, confused, and/or stuck at times. **This is not a defect -- it means you're doing the course right.** When it happens, don't wait for things to make sense on their own: *Ask questions* of me and your classmates and take action to make sense of the material. 
3. **Good management of time, tasks, and information.** Understanding the material won't help you if you procrastinate, skip reading announcements, or don't use a calendar. All course information will be clearly laid out for you, but it's up to you to import that information into your own lives and act on it. 

If you can commit to these three things, then I have every expectation that you'll succeed in the course, no matter what your math background or perceived math skill is. 

## How MTH 302 is structured 

### Course level learning objectives and catalog description

**Official catalog description:** Matrix algebra and determinants. Introduction to the theory of differential equations. Methods of solution (including Laplace transform techniques) of linear equations, as well as some special types of nonlinear equations. Applications in physical, biological, and social sciences. Offered fall and winter semesters. *Prerequisite*: MTH 203. *Credits*: 4. 

After successful completion of the course, you will be able to…

1. Explain the geometric and physical significance of the concepts of linear algebra.
2. Apply linear algebra and differential equations to mathematical modeling.
3. Apply computational and analytical techniques to formulate, solve, and interpret
mathematical models.
1. Apply quantitative methods to ordinary differential equations.
2. Use computer algebra systems such as Maple®, Matlab®, and/or Mathematica®.
3. Explain how concepts in linear algebra and differential equations can be generalized to
different contexts.
7. Use modern computer tools (Python, specifically the SymPy and NumPy packages) to analyze and solve problems involving linear algebra and differential equations. 

### How MTH 302 is set up 

The course content is split up into four distinct modules: 

- **Linear algebra:** Systems of linear equations; row reduction and solving systems; linear combinations and span; linear independence; matrices and matrix algebra; inverses and determinants of matrices; eigenvalues and eigenvectors of matrices. 
- **Differental equations:** Basic terminology and concepts; slope fields; linear first-order DEs; nonlinear first-order DEs; Euler's method. 
- **Systems of differential equations:** Solving systems of DEs using eigenvalues; homogeneous first-order systems; systems with linearly independent eigenvectors; systems without linearly independent eigenvectors; nonhomogeneous systems. 
- **Further explorations:** Higher-order DEs and their connection to systems; Laplace transform methods. 

There are many sub-topics that you'll be learning and practicing throughout the course. However, there are twelve **Foundational Skills** that are essential for all students to master. These are listed in Appendix A, Foundational Skills. 

### The flow of a typical week 

While we meet only on Tuesdays and Thursdays, you're expected to work actively on the course throughout the week. Each class meeting has activities for you to do *before*, *during* and *after* the class. Specific kinds of assignments are given **in bold face** and are explained fully in the next section. 

- *Before each class:* You'll be asked to complete a **Class Prep** assignment where you'll do a combination of reading, video viewing, and other activities then answering basic questions about it. This way, you'll come to class ready to work, and we can keep lecturing in class to a minimum.
- *During class:* Class meetings will be focused on *answering questions* and *doing active work*. Much of this work will be turned in later. We'll also sometimes use class meetings for assessment.  
- *In between classes:* You'll be working on the Class Prep for the next class meeting; completing **Practice Sets** on WeBWorK, a platform for doing online exercises; writing up the work you do in groups during class time to turn in as **Application and Analysis** assignments; and completing **Miniprojects**. You can also use this time to come to drop-in hours or ask questions via email. 

Due dates on these assignments happen on a consistent schedule: 

- Practice Sets are always due at 11:59pm ET on Sundays. 
- Class Preps are always due at 11:59pm ET on Mondays and Wednesdays (the night before the class meeting).
- Application/Analysis sets are always due at 11:59pm ET on Wednesdays. 

Visually, a typical week in MTH 302 looks like this: 

![Weekly workflow in MTH 302](weekly-workflow.png)

Due dates on Miniprojects vary; see below for details. 

---

## Assignments and grades

### Overall approach to grades in MTH 302

The way grades work in MTH 302 is different from what you might have experienced. In MTH 302: 

- **Almost none of your assignments have point values**. The ones that do have point values, are given either 0 or 1 points only. Therefore there is **no partial credit and no averaging**. 
- Instead, assignments have **specifications** which are descriptions of what constitutes "acceptable" work. These are given in detail in the document *Standards for Student Work* which you can find on Blackboard in the *Syllabus and Calendar* area. When you submit an assignment, I will read it carefully and compare it with the standards, and simply determine whether it meets the specifications or not. 
- After I evaluate your work, in most cases you will receive **detailed feedback** that will tell you whether your work meets the standards, and if not, the feedback will tell you what was missing and how you might go about fixing it. 
- Then, on almost every piece of work, you will have the chance to **retry** the assignment, get more feedback, and repeat this **feedback loop** until the work meets our specifications. 
- Your course grade is not based on point totals or averages (because most items don't have point values). Instead, the course grade is based on **how many important learning tasks you've accomplished** by the end of the semester, using a simple table that's given below. 

This process, using specifications and feedback loops rather than points and averages, is actually how evaluation of work happens in most situations outside of college. In your future jobs, for example, you'll be reviewed regularly by your manager; it's not a "one and done" situation where you get a point score and then the process is over. Instead, in a real job, you get feedback and coaching on how to improve, and then you act on the feedback and show the boss that you have improved. 

Therefore grades in MTH 302 are based not on your ability to do good work at a single point in time, but rather on your ability to **eventually learn the material** by acting on feedback from previous attempts. 

I've been using this grading method since 2017, originally in MTH 325 and now in all my classes. We do things this way because **learning takes time**, and I believe grading your work based on a single point of data such as a quiz or test and then averaging all of those data is not only inaccurate, but statistically invalid and even unethical. Feedback loops are how all human learning takes place. So this seems like the best way to do grading. 

Those are the main concepts; the details are in the rest of the syllabus. Most students need a week or two to adapt to this system, but then everything is fine. I encourage you to ask questions at any time so I can help you. 


### How you will be assessed 

There are five major kinds of assignments in MTH 302: 

- **Practice Sets:** These are weekly practice exercises over the basic computations we learn. These are completed using WeBWorK, a platform for online homework. Typically 5-7 problems per week are assigned and are graded 1 point if the answer is correct and 0 points otherwise. 
- **Class Prep:** These will give you the basic knowledge of terms, ideas, and basic concepts that will allow us to jump right into applications when we get to class. They involve reading portions of your textbook (and occasionally watching video), engaging in asking questions about what you read, and answering some simple questions about the content. 
- **Application and Analysis:** In class, we will work in groups on higher-level tasks involving application and analysis of the basics. You'll be responsible for individually completing this work that you start in groups during class, and turning it in to be checked for basic overall correctness. 
- **Skill Quizzes:** Each Thursday, we'll take time in class for a timed quiz over a subset of the twelve Foundational Skills found in Appendix A. Each skill will appear on *three consecutive quizzes* so you'll have three attempts at each. 
- **Miniprojects:** These are longer-form problems that involve deeper applications of the concepts from class, on applications in a variety of domains and in problems whose solutions require computer tools and good technical writing. 

Each of these assignments is graded as follows: 

| Assignment | Basis for grading | What's recorded on Blackboard | 
| :---------: |  :---------: |  :---------: | 
| Practice Sets | Correctness | Nothing; scores are kept on WeBWorK | 
| Class Prep | Completeness and effort only | *Complete* or *Incomplete* (will appear as a green check or red x) | 
| Application/Analysis | Completeness and overall correctness | *Success*, *Retry*, or *Incomplete* | 
| Skill Quizzes | Overall correctness | *Success* or *Retry* | 
| Miniprojects |  Completeness, overall correctness, writing, and presentation | *Success*, *Retry*, or *Incomplete* | 

The document *Standards for Student Work* gives a complete description of the specific criteria used for grading these assignments.  

Additionally, we will have a brief but comprehensive **final exam**, graded using points (out of 100) whose schedule is on the course calendar. 

## Course grades 



## Revisions and reattempts 

## Academic integrity and honesty 

## Course Policies 

### Attendance, absence, and participation

### Deadlines and late work 

### Technology skills and support 

### Instructor availability and message responses

### Special accommodations and basic needs 

## About the instructor 

I'm Robert Talbert, the professor for this course. I'm a Professor of Mathematics and also work in the president's office as Presidential Fellow for the Advancement of Learning. This is my 31st year of teaching overall (not counting tutoring gigs). I have a Ph.D. in Mathematics from [Vanderbilt University](http://vanderbilt.edu) and a B.S. degree from [Tennessee Tech University](http://www.tntech.edu). 

I was, at best, a thoroughly mediocre math student in school until my senior year of high school, when I had a teacher for Calculus (hi, Mrs. Allen) who stopped trying to cram things into my head and instead showed me the basics -- and then backed off, and let me work things out on my own (with support if I got stuck). Basically, this is how I teach today. 

After a two-year gig as a Psychology major in college, I changed my major to math after a late-night dare from my roommate (long story) and, to my great surprise, I fell in love with the subject. I ended up getting a Ph.D. working in an obscure area at the intersection of abstract algebra and geometry, and I also discovered I loved teaching math to college students. So I went on to spend 14 years teaching in [small liberal arts colleges](http://franklincollege.edu) before coming to GVSU in 2011.

Now, I teach computer scientists and engineers how to think like mathematicians, I do research on how to make college teaching better, and I coordinate large-scale teaching/learning projects for President Mantella's office. (The fancy active learning classroom in which we are meeting, is one of my projects.) When nobody is looking, I am working on my skills in Python and R, learning data science, and dabbling in project management. 

I live in Allendale with my wife, two teenage kids (there's another kid who lives in Greenville), and three cats. I'm a long-time bass guitar player and a lover of the outdoors. I aspire to spend more time in a kayak or on a bike than in front of a computer. You can read more about what I'm thinking and doing at my website, [rtalbert.org](https://rtalbert.org), or at my "other blog" [Grading for Growth](https://gradingforgrowth.com) about alternative grading practices which I co-author with my GVSU colleague Prof. David Clark. I'm also on Twitter at [@RobertTalbert](http://twitter.com/RobertTalbert) and on [LinkedIn](https://www.linkedin.com/in/roberttalbert/). I will accept any connection request on LinkedIn from a student! 

## Appendix A: Foundational Skills 

The following twelve skills are considered essential skills for competency in the course. Your course grade is partially determined by how many of these you can demonstrate mastery. The ones labelled "LA" are related to linear algebra; the ones labelled "DE" are related to differential equations. 

- LA.1: I can solve a system of linear equations by converting it into an augmented matrix and putting into reduced row echelon form. 
- LA.2: I can determine if a vector is in the span of a collection of other vectors. 
- LA.3: I can determine if a collection of vectors is linearly independent. 
- LA.4: I can add, subtract, and multiply matrices. 
- LA.5: I can determine if a matrix is invertible, using information about the matrix. 
- LA.6: I can find the eigenvalues and eigenvectors of a $2 \times 2$ and $3 \times 3$ matrix. 
- DE.1: I can solve a linear, homogeneous first-order differential equation using integration. 
- DE.2: I can solve a separable first-order differential equation using integration. 
- DE.3: I can generate a numerical solution to a first-order differential equation using Euler's method. 
- DE.4: I can solve a linear system of two differential equations. 
- DE.5: I can solve a linear, homogeneous second-order differential equation. 
- DE.6: I can compute basic Laplace transforms.  

## Appendix B: Course Calendar 

You can access the calendar directly at this link: https://calendar.google.com/calendar/u/1?cid=Y183MGRiN2ExZjIyNzc0OTYxOTEwY2IxN2ZlNzRhZjBjMDNhNzg3NDY5YjhlMzNiYWE0OGNhYzNlNTZjMjNhNDAwQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20  It's also embedded on Blackboard in the *Syllabus and Calendar* area, as well as below (although some web versions may not display it). 

<iframe src="https://calendar.google.com/calendar/embed?src=c_70db7a1f22774961910cb17fe74af0c03a787469b8e33baa48cac3e56c23a400%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

## Appendix C: Course Tools and Links

- **Blackboard**: http://lms.gvsu.edu, then look for your section of MTH 302. 
- **Google Colab:** This is our platform for using Python to do linear algebra and differential equations. Go to https://colab.research.google.com/ and sign in with your GVSU Google account. 
- **Perusall**: This is for doing reading and other activities for  http://perusall.com (Use the invite code posted to Blackboard in the *Important Links* area; log in to access course materials) 
- **Calendly**: This is for scheduling appointments with me outside of the usual drop-in hours. Go to https://calendly.com/robert-talbert then choose the kind of appointment you want, then pick any open 20-minute time slot. Note, appointment slots are limited. 