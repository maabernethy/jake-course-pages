---
layout: default
permalink: /eecs-598-fall-2013
title: "EECS598: Prediction and Learning: It's Only a Game"
course_name: "Prediction and Learning: It's Only a Game"
course_number: "EECS 598 - Fall 2013"
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
  info="EECS 598-006, Fall 2015, 3 Credits"
  instructor_name="Jacob Abernethy"
  instructor_link="http://web.eecs.umich.edu/~jabernet/"
  instructor_info="Office: 3765 BBB, Email: jabernet_at_umich_dot_edu"
  time="TuTh 3:00-4:30pm"
  place="3433 EECS Bldg"
  office_hours="Tuesdays 1-2pm"
%}

#### Course Description
<div class="divider mini-divider"></div>

This course will focus on the problem of prediction, learning, and
decision making, yet the underlying theme will involve game playing,
betting and minimax analysis. We will begin by introducing the
classical Weighted Majority Algorithm, and more broadly the problem
of “adversarial online learning” and “regret minimization”, and this
will launch us into topics such as von Neumann’s Minimax Theorem,
multi-armed bandit problems, Blackwell Approachability, calibrated
forecasting, and proper scoring rules. I intend to spend some time on
applications to finance, like repeated gambling, universal portfolio
selection, and option pricing.

**Prerequisites:** Familiarity with the analysis of algorithms,
probabilistic analysis, and several similar topics. EECS 545 (Machine
Learning) will be quite helpful but not strictly necessary. The
material is going to be about 90% "theory" and thus potential students
must have a strong mathematical background. We shall rely heavily on
techniques from calculus, probability, and convex analysis, but many
tools will be presented in lecture.

**Coursework:** There will be a small number of problem sets, and the
final project for the course will consist of the option to do
independent research or to give a literature review presentation to the
class.

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


#### Grade Breakdown
<div class="divider mini-divider"></div>

<table>
  <tr>
    <td class="info_label">35% for Homeworks</td>
    <td class="info_data">There will be 3-4 problem sets through the semester</td>
  </tr>
  <tr>
    <td class="info_label">50% for Final Project</td>
    <td class="info_data">[(NEW!!) <a href="homeworks/project_ideas.pdf">Summary of Project Ideas</a>] Students can do a final project on reviewing some research paper, doing novel research, or implementing some algorithms in an interesting way. More details on this to come.</td>
  </tr>
  <tr>
    <td class="info_label">15% for Participation</td>
    <td class="info_data">Students must scribe a lecture, participate in class, and can receive participation credit for answering some challenge questions. I will try to make enough opportunities for this.</td>
  </tr>
</table>

#### References
<div class="divider mini-divider"></div>

The course will not have any official textbook. But the following book
(which influenced the choice of title for the course) will be quite
helpful:

*   "Prediction, Learning, and Games" by Nicolo Cesa-Bianchi and Gabor Lugosi

There is another text that has a few chapters I would like to cover:

*   "Probability and Finance: It's Only a Game!" by Glen Shafer and Vladimir Vovk

In the last several years, several surveys have come out that explore
several topics that we shall cover. I will link to them here, and will
mention them in various lectures when appropriate:

*   [The Multiplicative Weights Update
Method](http://www.cs.princeton.edu/~arora/pubs/MWsurvey.pdf) by
Sanjeev Arora, Elad Hazan, and Satyen Kale.
*   [Online Learning and Online Convex
Optimization](http://www.cs.huji.ac.il/~shais/papers/OLsurvey.pdf)
survey by Shai Shalev-Shwartz.
*   [The convex optimization approach to regret
minimization](http://ie.technion.ac.il/~ehazan/papers/shalom.pdf)
survey by Elad Hazan.
*   [Sasha Rakhlin's Lecture
Notes](http://www-stat.wharton.upenn.edu/~rakhlin/courses/stat928/stat928_notes.pdf).


#### Scribe Notes
<div class="divider mini-divider"></div>

1. [Lecture 1, 9/4](./notes/lec1_090413.pdf): Course Overview and Intro to Online Learning
2. [Lecture 2, 9/9](./notes/lec2_090913.pdf): Weighted Majority Algorithm
3. [Lecture 3, 9/11](./notes/lec3_091113.pdf): The Exponential Weights Algorithm
4. [Lecture 4, 9/16](./notes/lec4_091613.pdf): The Action Setting and Hyperexperts
5. [Lecture 5, 9/18](./notes/lec5_091813.pdf): The Fixed-Share Forecaster
6. [Lecture 6, 9/23](./notes/lec6_092313.pdf): Lower Bounds and Game Theory I
7. [Lecture 7, 9/25](./notes/lec7_092513.pdf): Game Theory II: Nash Equilibria and von Neumann
8. [Lecture 8, 9/30](./notes/lec8_093013.pdf): Game Theory III: Proof of Minimax Thm using Hedge Alg
9. [Lecture 9, 10/02](./notes/lec9_100213.pdf): Applications of Minimax: LP and Boosting
10. [Lecture 10, 10/07](./notes/lec10_100713.pdf): Boosting and Perceptron Algorithms
11. [Lecture 11, 10/09](./notes/lec11_100913.pdf): Perceptron and Universal Portfolio Selection
12. [Lecture 12, 10/16](./notes/lec12_101613.pdf): Online Convex Optimization
13. [Lecture 13, 10/21](./notes/lec13_102113.pdf): Universal Portfolios Review and Online Convex Optimization
14. [Lecture 14, 10/23](./notes/lec14_102313.pdf): Game-theoretic Probability in Finance
15. [Lecture 15, 10/28](./notes/lec15_102813.pdf): Online Convex Optimization: Part III
16. [Lecture 16, 10/30](./notes/lec16_103013.pdf): Follow the Regularized Leader
17. [Lecture 17, 11/04](./notes/lec17_110413.pdf): FTRL and Applications of OCO
18. [Lecture 18, 11/06](./notes/lec18_110613.pdf): The Bandit Setting
19. [Lecture 19, 11/11](./notes/lec19_111113.pdf): UCB Algorithm and the Adversarial Bandit Problem
20. [Lecture 20, 11/13](./notes/lec20_111313.pdf): EXP3 Algorithm
21. [Lecture 21, 11/18](./notes/lec21_111813.pdf): Bandit Algorithm and Blackwell Approachability
22. [Lecture 22, 11/20](./notes/lec22_112013.pdf): Blackwell's Approachability Theorem
23. [Lecture 23, 12/02](./notes/lec23_120213.pdf): B.A.T. Review and Calibrated Forecasting
24. [Lecture 24, 12/04](./notes/lec24_120413.pdf): Generalized Calibration and Correlated Equilibria


#### Homeworks
<div class="divider mini-divider"></div>

1.  [Homework #1](./homeworks/hw1.pdf) - Due 9/25/2013
2.  [Homework #2](./homeworks/hw2.pdf) - Due 10/28/2013
3.  [Homework #3](./homeworks/hw3.pdf) - Due 11/27/2013

#### Course Schedule and Additional Info
<div class="divider mini-divider"></div>

{% include eecs598_fall2013/schedule.html %}
