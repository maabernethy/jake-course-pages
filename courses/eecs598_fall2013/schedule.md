<table>
  <colgroup>
    <col width="10%" />
    <col width="40%" />
    <col width="50%" />
  </colgroup>

  <tr>
   <td><strong>Date</strong>
   <td><strong>Schedule of Topics</strong>
   <td><strong>Links + Notes</strong>

  <tr>
   <td>9/4/2013
   <td>
      <ul>
      <li>Introduction
      <li>Learning theory discussion
      <li>Prediction with expert advice
      <li>The halving algorithm
      <li>Example: halving on permutations for "predictive sorting"
   <td>
      <ul>
      <li markdown="span">[The Multiplicative Weights Update Method](http://www.cs.princeton.edu/~arora/pubs/MWsurvey.pdf)</li>
      <li markdown="span">[Notes](http://www.cs.berkeley.edu/~bartlett/courses/281b-sp08/21.pdf) from Peter Bartlett's Course</li>


  <tr>
   <td>9/9/2013
   <td>
      <ul>
      <li>Review of halving algorithm on permutations
      <li>The weighted majority algorithm
      <li>Proving a mistake bound on Weighted Majority
   <td>
      <ul>
      <li markdown="span">[Scribe notes](http://web.eecs.umich.edu/~jabernet/eecs598course/web/notes/lec1_090413.pdf) posted from Lecture 1 </li>
      <li markdown="span"> An [open problem](http://colt2010.haifa.il.ibm.com/papers/OpenProblemAbernethy.pdf) I posed regarding "learning rankings" from COLT 2010 </li>
      <li markdown="span"> Apparently [a solution](http://jmlr.org/proceedings/papers/v23/hazan12b/hazan12b.pdf) to this open problem by Elad Hazan, Satyen Kale, and Shai Shalev-Shwartz </li>
      <li markdown="span">Homework to be released soon! It will be due 9/25/2013.</li>


  <tr>
   <td>9/11/2013
   <td>
      <ul>
      <li>WMA generalized: Exponential Weights Algorithm
      <li>The "Hedge Setting"
   <td>
      <ul>
      <li markdown="span"> [Homework 1](http://web.eecs.umich.edu/~jabernet/eecs598course/web/homeworks/hw1.pdf) is available, it's due 9/25/2013.</li>
      <li markdown="span"> [Notes](http://seed.ucsd.edu/Onlinecrs/rsrc/Onlinecrs/LessonNo2/talk2.handout.pdf) from Yoav Freund's course</li>


  <tr>
   <td>9/16/2013
   <td>
      <ul>
      <li>More the the action setting vs prediction setting
      <li>A new "additive" bound
      <li>Variants of weighted majority (different priors, fixed share forecaster, changing learning rates)
      <li>Hannan-consistency and the no-regret property
   <td>
      <ul>
      <li markdown="span">Orig "Hedge Setting" introduced by Freund and Schapire's original Adaboost [paper](href="http://www.face-rec.org/algorithms/Boosting-Ensemble/decision-theoretic_generalization.pdf)</li>
      <li markdown="span">I showed an "additive bound" and a "multiplicative bound" in class on 9/16. These can be found in the [PLG book](http://www.amazon.com/Prediction-Learning-Games-Nicolo-Cesa-Bianchi/dp/0521841089) Theorems 2.2 and 2.4.</li>
      <li>I needed an inequality in class (regarding log E[exp(sX)]) which I didn't prove, but it's pretty classical and you can find the result in Lemma A.1 in the PLG book.</li>


  <tr>
   <td>9/18/2013
   <td>
      <ul>
      <li>Fixed-share forecaster
   <td>
      <ul>
      <li>This result is actually reasonably well-written up in the PLG book, section 5.2. Theorem 5.2 proves the bound on the hyperexperts.  Theorem 5.1 makes the connection between the complex algorithm making hyperexpert weight updates, and the efficient version.</li>


  <tr>
   <td>9/23/2013
   <td>
      <ul>
      <li>Lower bounds for 2 and N experts
      <li>Game Theory I
      <li>Two-player games
   <td>
      <ul>
      <li>The lower bound I proved in class, with the important details, can roughly be found in PLG section 3.7. The key lemmas are in Appendix A.1.6.</li>


  <tr>
   <td>9/25/2013
   <td>
      <ul>
      <li>Game Theory II
      <li>Nash's Theorem via Brouwer Fixed-point Theorem
      <li markdown="span">Guest Lecturer: [Satyen Kale](href="http://www.satyenkale.com/)</li>
      <li> Zero-sum games
      <li>von Neumann Minimax Theorem
   <td>
      <ul>
      <li markdown="span">Here are [the notes](http://agte-2011.wikischolars.columbia.edu/file/view/Notes+4.pdf) proving Nash's Theorem, which includes the proof of Sperner's Lemma that can be used to establish the Brouwer Fixed-point Theorem.</li>


  <tr>
   <td>9/30/2013
   <td>
      <ul>
      <li>Game Theory III
      <li>Proof of Minimax Thm using Hedge Alg
      <li>Computing approximate equilibria
   <td>
      <ul>
      <li markdown="span"> More on this trick can be found in the Arora/Hazan/Kale [survey](http://www.satyenkale.com/papers/mw-survey.pdf), where I first saw this technique. There's a more general version proven in PLG section 7.2.</li>


  <tr>
   <td>10/2/2013
   <td>
      <ul>
      <li>Introduction to Boosting
      <li>Boost by Majority
      <li>Boosting as sequential duality optimization
   <td>
      <ul>
      <li markdown="span">There a new Boosting [book](https://mitpress.mit.edu/books/boosting) out by Rob Schapire and Yoav Freund which is excellent. The relationship between online learning, the minimax theorem, and boosting, is in Chapter 6.</li>


  <tr>
   <td>10/7/2013
   <td>
      <ul>
      <li>More on Boosting
      <li>The Perceptron Algorithm
   <td>
      <ul>
      <li markdown="span">There are a number of good writeups of the perceptron regret bound. [Here is one](http://www.cs.cmu.edu/~avrim/ML09/lect0126.pdf)</li>


  <tr>
   <td>10/9/2013
   <td>
      <ul>
      <li>Recap for perceptron algorithm
      <li>Log loss and gambling
      <li>Constant Rebalanced Portfolios
      <li>Universal portfolio strategies
      <li>Cover's UCRP algorithm and analysis
   <td>
      <ul>
      <li markdown="span">Tom Cover's [original paper](http://www-isl.stanford.edu/~cover/papers/paper93.pdf) on Universal Portfolios</li>
      <li markdown="span">The [source of the easier analysis](http://link.springer.com/article/10.1023%2FA%3A1007530728748#page-1) source of the UCRP algorithm, with discussions of transaction costs</li>


  <tr>
   <td>10/14/2013
   <td>FALL BREAK - NO CLASS!!!!!
   <td>


  <tr>
   <td>10/16/2013
   <td>
      <ul>
      <li markdown="span">Guest Lecturer: [Ambuj Tewari](http://dept.stat.lsa.umich.edu/~tewaria/) Introduction to Online Convex Optimization</li>
      <li>Be The Leader etc.
   <td>


  <tr>
   <td>10/21/2013
   <td>
      <ul>
      <li>Review of Universal Portfolios
      <li>Review of Online Convex Optimization model
      <li>Examples applications of OCO
      <li>Online Gradient Descent algorithm
   <td>
      <ul>
      <li markdown="span">Original [OCO + gradient descent](http://machinelearning.wustl.edu/mlpapers/paper_files/icml2003_Zinkevich03.pdf) paper by Zinkevich</li>
      <li>Several good survey papers on OCO now, see links on course website


  <tr>
   <td>10/23/2013
   <td>
      <ul>
      <li>Regret bound for Online Gradient Descent
      <li markdown="span">Guest Lecturer: [Rafael Frongillo](http://www.cs.berkeley.edu/~raf/)</li>
      <li>Game-theoretic Probability in Finance
   <td>
      <ul>
      <li markdown="span">Lecture based on ideas from [this book](http://www.amazon.com/Probability-Finance-Its-Only-Game/dp/0471402265)</li>


  <tr>
   <td>10/28/2013
   <td>
      <ul>
      <li>More on algorithms for OCO
      <li>Follow the Leader
      <li>Application: Online Density Estimation
   <td>
      <ul>
      <li markdown="span">Earlly [work by Azoury and Warmuth](http://arxiv.org/pdf/1301.6677) on density estimation</li>
      <li markdown="span"> [General results](http://ie.technion.ac.il/~ehazan/papers/log-journal.pdf) for logarithmic regret algorithms by Hazan, Agarwal, and Kale</li>


  <tr>
   <td>10/30/2013
   <td>
      <ul>
      <li>Follow the Regularized Leader (FTRL)
      <li>Generic regret bound for FTRL
      <li>Guest visit from CRLT by Tershia
   <td>


  <tr>
   <td>11/4/2013
   <td>
      <ul>
      <li>Online Convex Optimization III
      <li>OCO Application 1: Convex Optimization
      <li>OCO Application 2: risk bound in IID setting
   <td>
      <ul>
      <li markdown="span">The "online to batch conversion" idea started with [this nips paper](http://books.nips.cc/papers/files/nips14/LT07.pdf) from 2004</li>


  <tr>
   <td>11/6/2013
   <td>
      <ul>
      <li>Student HW2 presentations
      <li>The multi-armed bandit setting
      <li>Greedy algorithm
   <td>
      <ul>
      <li markdown="span">Nearly all results from the next couple of lectures can be found in Bubeck and Cesa-Bianchi's [survey of regret analysis for bandit problems](http://www.princeton.edu/~sbubeck/SurveyBCB12.pdf)</li>


  <tr>
   <td>11/11/2013
   <td>
      <ul>
      <li>The UCB Algorithm
      <li>The adversarial bandit setting
      <li>Definition of EXP3 Algorithm
   <td>
      <ul>
      <li markdown="span">Peter Auer was [the first to propose](http://jmlr.org/papers/volume3/auer02a/auer02a.pdf) the UCB algorithm for a finite-time analysis of the multi-armed bandit setting</li>


  <tr>
   <td>11/13/2013
   <td>
      <ul>
      <li>EXP3 Regret Bound and Proof
      <li>Online linear optimization in the bandit setting
   <td>
      <ul>
      <li markdown="span">[Bandit slides](http://web.eecs.umich.edu/~jabernet/eecs598course/web/notes/bandit_talk_slides.pdf) from class presentation</li>


  <tr>
   <td>11/18/2013
   <td>
      <ul>
      <li>Bandit OLO and the use of self-concordant regularization
      <li>Introduction to Blackwell Approachability
   <td>
      <ul>
      <li markdown="span">My [2011 COLT paper](http://jmlr.org/proceedings/papers/v19/abernethy11b/abernethy11b.pdf) does a reasonably good job describing the Approachability setting</li>


  <tr>
   <td>11/20/2013
   <td>
      <ul>
      <li>Blackwell Approachability Algorithm and Convergence
      <li>Reductions between Approachability and No-Regret
   <td>
      <ul>
      <li markdown="span">The [COLT paper](http://jmlr.org/proceedings/papers/v19/abernethy11b/abernethy11b.pdf) describes the reduction using cone duality, but there has been some recent work that showed how to avoid the use of cones and instead uses an OCO reduction. But the paper doesn't appear to be available yet, I'll contact the authors for more.</li>


  <tr>
   <td>11/25/2013
   <td> OFFICE HOUR - NO CLASS
   <td>


  <tr>
   <td>11/27/2013
   <td>PRE-THANKSGIVING - NO CLASS
   <td>


  <tr>
   <td>12/2/2013
   <td>Approachability, Calibrated Forecasting, and No Internal Regret
   <td>


  <tr>
   <td>12/4/2013
   <td>
      <ul>
      <li>Reductions between learning problems
      <li>Correlated Equilibria
   <td>


  <tr>
   <td>12/9/2013
   <td>STUDENT PRESENTATIONS
   <td>


  <tr>
   <td>12/11/2013
   <td>POSTER SESSION
   <td>
