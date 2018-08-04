---
layout: default
permalink: /eecs-598-fall-2015
title: "EECS598: Theoretical Foundations of Machine Learning"
course_name: Theoretical Foundations of Machine Learning
course_number: "EECS 598 - Fall 2015"
---

{% include sidenav.html
  section1="Course Information"
  section1_link="#course-information"
  section2="Course Description"
  section2_link="#course-description"
  section3="Topics and Algorithms"
  section3_link="#topics-and-algorithms"
  section4="Grade Breakdown"
  section4_link="#grade-breakdown"
  section5="References"
  section5_link="#references"
  section6="Lecture Notes"
  section6_link="#scribe-notes"
  section7="Homeworks"
  section7_link="#homeworks"
%}

#### Course Information
<div class="divider mini-divider"></div>

{% include course_info.html
  info="EECS 598-005, Fall 2015, 3 Credits"
  instructor_name="Jacob Abernethy"
  instructor_link="http://web.eecs.umich.edu/~jabernet/"
  instructor_info="Office: 3765 BBB, Email: jabernet_at_umich_dot_edu"
  time="TuTh 3:00-4:30pm"
  place="1005 DOW"
  office_hours="Wednesdays 1:30-3pm"
%}

#### Course Description
<div class="divider mini-divider"></div>

This course will study theoretical aspects of prediction problems, where we seek to understand themathematical underpinnings of machine learning. A primary objective of the class is to bring students to the frontiers of research in this area. The course will cover, among other things, concentration inqualities, uniform deviation bounds, Vapnik-Chervonenkis Theory, Rademacher Complexity, margin bounds, results for kernel methods, boosting, generalization bounds for artificial neural networks, online learning theory and regret minimization. Along the way, we will dive into several related topics, including connections to convex optimization, minimax equilibrium in games, multi-armed bandit problems, calibration, sequential portfolio selection, option pricing, and differential privacy.

**Prerequisites:** Familiarity with the analysis of algorithms, probabilistic analysis, and several similar topics. EECS 545 (Machine Learning) will be quite helpful but not strictly necessary. The material is going to be about 90% "theory" and thus potential students must have a strong mathematical background. We shall rely heavily on techniques from calculus, probability, and convex analysis, but many tools will be presented in lecture.

**Coursework:** There will be 5 problem sets, and the final project for the course will consist of the option to do independent research or to give a literature review presentation to the class.

#### Grade Breakdown
<div class="divider mini-divider"></div>

{% include grade_breakdown.html
  header1="50% for Homeworks"
  content1="There will be 5 problem sets through the semester"
  header2="40% for Final Project"
  content2="Students can do a final project on reviewing some research paper, doing novel research, or implementing some algorithms in an interesting way. More details on this to come."
  header3="10% for Participation"
  content3="Students must scribe 1-2 lectures, participate in class, and can receive participation credit for answering some challenge questions. I will try to make enough opportunities for this."
%}

#### Topics and Algorithms
<div class="divider mini-divider"></div>

- Online Learning and Regret Minimization
- The Weighted Majority Algorithm
- The Perceptron Algorithm
- Boosting
- Convex Optimization and Convex Analysis
- Bregman Divergences
- Follow the Regularized Leader and Variants
- Linear Programming Duality
- Game Theory and the Minimax Theorem
- Multi-Armed Bandits
- EXP3 Algorithm and Variants
- Internal Regret and Correlated Equilibria
- Blackwell's Approachability Theorem
- Calibrated Forecasting
- Reductions Between Learning Frameworks
- Universal Portfolios
- Gambling, Prediction, and Log Loss
- Option Pricing and Black-Scholes



#### References
<div class="divider mini-divider"></div>

Roughly half of the course will follow material from the following
text:


  - "[Foundations of Machine Learning](http://www.amazon.com/Foundations-Machine-Learning-Adaptive-Computation/dp/026201825X)"
by Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar

There is another text that has a few chapters I would like to cover:


  * "Prediction, Learning, and Games," by Nicolo Cesa-Bianchi and
Gabor Lugosi

In the last several years, several surveys have come out that explore
several topics that we shall cover. I will link to them here, and will
mention them in various lectures when appropriate:


  * [The Multiplicative Weights Update
Method](http://www.cs.princeton.edu/~arora/pubs/MWsurvey.pdf) by
Sanjeev Arora, Elad Hazan, and Satyen Kale.
  * [Online Learning and Online Convex
Optimization](http://www.cs.huji.ac.il/~shais/papers/OLsurvey.pdf)
survey by Shai Shalev-Shwartz.
  * [The convex optimization approach to regret
minimization](http://ie.technion.ac.il/~ehazan/papers/shalom.pdf)
survey by Elad Hazan.
  * [Sasha Rakhlin's Lecture
Notes](http://www-stat.wharton.upenn.edu/~rakhlin/courses/stat928/stat928_notes.pdf).

#### Scribe Notes
<div class="divider mini-divider"></div>

1. [Lecture 1, 9/8](./notes/lec1_090815.pdf): Course Overview and Linear Algebra Review
2. [Lecture 2, 9/10](./notes/lec2_091015.pdf): Convex Analysis
3. [Lecture 3, 9/15](./notes/lec3_091515.pdf): Concentration Inequalities
4. [Lecture 4, 9/17](./notes/lec4_091715.pdf): Hoeffding’s Inequality and Martingales
5. [Lecture 5, 9/22](./notes/lec5_092215.pdf): PAC Learning Basics
6. [Lecture 6, 9/24](./notes/lec6_092415.pdf): Risk and PAC-Learnible Class
7. [Lecture 7, 9/29](./notes/lec7_092915.pdf): General PAC Guarantee
8. [Lecture 8, 10/01](./notes/lec8_100115.pdf): PAC Guarantee for Infinite Sets and Growth Function
9. [Lecture 9, 10/06](./notes/lec9_100615.pdf): Relations between Lectures and Sauer’s Lemma
10. [Lecture 10, 10/08](./notes/lec10_100815.pdf): PAC Learning Lower Bounds
11. [Lecture 11, 10/13](./notes/lec11_101315.pdf): Margin Theory
12. [Lecture 12, 10/15](./notes/lec12_101515.pdf): Noisy Setting and Rademacher Complexity
13. [Lecture 13, 10/27](./notes/lec13_102715.pdf): Rademacher Complexity and Massart's Lemma
14. [Lecture 14, 10/29](./notes/lec14_102915.pdf): Growth Function Generalization Bound and Online Learning
15. [Lecture 15, 11/03](./notes/lec15_110315.pdf): Neural Networks Theory
16. [Lecture 16, 11/05](./notes/lec16_110515.pdf): Perceptron and Exponential Weights Algorithm
17. [Lecture 17, 11/10](./notes/lec17_111015.pdf): Exponential Weights Algorithm and Game Theory
18. [Lecture 18, 11/12](./notes/lec18_111215.pdf): Nash’s Theorem and Von Neumann’s Minimax Theorem
19. [Lecture 19, 11/17](./notes/lec19_111715.pdf): Fast Rates I
20. [Lecture 20, 11/19](./notes/lec20_111915.pdf): Fast Rates II
21. [Lecture 21, 12/01](./notes/lec21_120115.pdf): Bandit Problem
22. [Lecture 22, 12/03](./notes/lec22_120315.pdf): Adversarial Multi-Armed Bandits and EXP3
23. [Lecture 23, 12/08](./notes/lec23_120815.pdf): Online Convex Optimization


#### Homeworks
<div class="divider mini-divider"></div>

1.  [Homework #1](./homeworks/hw1.pdf) - Due 9/28/2015
2.  [Homework #2](./homeworks/hw2.pdf) - Due 10/16/2015
3.  [Homework #3](./homeworks/hw3.pdf) - Due 10/30/2015
4.  [Homework #4](./homeworks/hw4.pdf) - Due 11/20/2015
5.  [Homework #5](./homeworks/hw5.pdf) - Due 12/10/2015
