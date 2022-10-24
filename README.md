# Interactive Python Code Snippets for Discrete Mathematics

![specialization logo](notebooks/images/logo_specialization.png)

This repository contains Python code snippets from the [Discrete Mathematics for Computer Science specialization at Coursera](https://www.coursera.org/specializations/discrete-mathematics) and its [accompanying textbook](http://discrete-math.tilda.ws/). Together with interactive puzzles in the specialization, these interactive code snippets will give you a deeper understanding of the underlying ideas. To run them, you don't need to install or configure anything on your machine. Click the badge to invoke the notebooks in the cloud:
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/index.ipynb)

## Table of Contents

### Mathematical Thinking in Computer Science
![First course logo](notebooks/images/logo_proofs.png)

#### [Proofs: Convincing Arguments](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/01_proofs_convincing_arguments.ipynb)

Why are some arguments convincing while others are not? What makes an argument convincing? How can you establish your argument in such a way that no room for doubt is left? How can mathematical thinking help us deal with this? In this chapter, we will start by digging into these questions. Our goal here is to learn by examples how to understand proofs, how to discover them on your own, how to explain them, and — last but not least — how to enjoy them: we will see how a small remark or a simple observation can turn a seemingly non-trivial question into one with an obvious answer.

#### [Finding an Example](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/02_finding_an_example.ipynb)

How can we know that an object with certain properties exists? In the previous chapter, we saw that it suffices to give an example of such an object, but finding an example might be a hard problem. One way to find an example is to go through all objects and check whether at least one of them meets the requirements. However, in many cases, the search space is enormous. A computer may help, but some reasoning that narrows the search space is important both for computer search and for “bare hands” work. In this chapter, we will learn various techniques for showing that an object exists and that an object is optimal among all objects (say, the smallest or largest object that meets the requirements).

#### [Recursion and Induction](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/03_recursion_and_induction.ipynb)

We will discover two powerful methods of defining objects, proving concepts, and implementing programs — recursion and induction. These two methods are regularly used in discrete mathematics and computer science. You will see them frequently in algorithms — for analyzing the correctness and running time of algorithms as well as for implementing efficient solutions. For some computational problems (for example, exploring networks), recursive solutions are the most natural ones.

The main idea of recursion and induction is to decompose a given problem into smaller problems of the same type. Recursion is often used for computing something whereas induction is used for proving things. Being able to see such decompositions into smaller steps is an important skill both in mathematics and programming. We will hone this skill by solving various problems.

#### [Logic](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/04_logic.ipynb)

Mathematical logic plays a crucial and indispensable role in creating convincing arguments. We use the rules and language of mathematical logic while writing code, reasoning and making decisions, and using computer programs. In this chapter, we’ll learn the basics of mathematical logic, and we’ll practice tricky and seemingly counterintuitive, yet logical aspects of mathematical logic. This will help us to write readable and precise code, and to formulate our thoughts rigorously and concisely.

#### [Invariants](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/05_invariants.ipynb)

“There are things that never change.” Apart from being just a philosophical statement, this phrase turns out to be an important idea in discrete mathematics and computer science. A property that is preserved during a process is called an invariant. Invariants are widely used in analyzing the behavior of algorithms, programs, and other processes. In this chapter, we will develop the important skill of finding the right invariant for a problem.

#### [Appendix: SAT and ILP Solvers](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/07_sat_and_ilp.ipynb)

In this chapter, we show how to use SAT and ILP solvers to handle difficult combinatorial problems in practice.


### Combinatorics and Probability
![Second course logo](notebooks/images/logo_combinatorics.png)

#### [Starting to Count](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/06_basic_counting.ipynb)

Counting is one of the basic mathematically related tasks we encounter on a daily basis. The main question here is the following: can we count the number of objects without listing all of them? This question arises naturally in various scenarios both in real life and in Computer Science. What is the number of phone numbers or license plates? What is the number of combinations one needs to brute force in order to crack a password? Is there a way to tell that an algorithm will run in a reasonable time before implementing and running it? All these questions are addressed by a mathematical field called combinatorics.

In this chapter, we consider the basic building blocks of combinatorics. All of them are easy to understand and at the same time are powerful enough to handle various non-trivial questions. To help you to develop an intuition, we consider short Python code snippets for generating the objects to be counted.

#### [Binomial Coefficients](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/07_binomial_coefficients.ipynb)

In how many ways one can select a team of five students out of ten students? What is the number of non-negative integers with at most five digits whose digits are decreasing? In how many ways one can get from the bottom left cell to the top right cell of a 6×6 grid, each time going either up or to the right? And why all these three numbers are equal? We’ll figure this out in this chapter!

#### [Advanced Counting](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/08_advanced_counting.ipynb)

In how many ways one can distribute ten candies to four kids? What is the number of credit card PINs with non-increasing digits? What is the number of non-negative integer solutions of an equation x1 + x2 + x3 + x4 = 10? It turns out that this is essentially the same problem. The corresponding selection scheme is known as combinations with repetitions. In this chapter, we derive a formula for counting such objects using a powerful stars-and-bars method. We’ll practice applying this method to many problems that have nothing in common on the first sight.

#### [Probability](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/09_probability.ipynb)

The word “probability” is used frequently in the everyday life. We often say that something is probable, or that one outcome looks more probable than another one. However, not always we can speak about probability as some number: for that, a mathematical model is needed. What is this mathematical model (probability space)? How to compute probabilities (if the model is given)? How to judge whether the model is adequate? What is conditional probability and Bayes’ theorem? How our plausible reasoning can be interpreted in terms of Bayes’ theorem? In this chapter, we cover these questions using simple examples of probability spaces and real life situations.

#### Random Variables

In the previous chapter, we discussed how to compute probabilities of random events: say, the probability of getting three heads out of seven coin tosses or the probability of winning a car if you switch the door after you see a goat behind the opened door. At the same time, an outcome of many random experiments is not just an event, but a number (a measurement of something). For example, one may want to estimate gambling winnings, or an income of a random person in a group of people, or the number of steps of a randomized algorithm. In this chapter, we discuss random variables, a mathematical model that allows to compute quantitative characteristics of random experiments.

#### Dice Games

In this chapter, we will apply accumulated knowledge to analyze a simple dice game. In the game, each of two players selects a dice from a given pool of dice. Then, they throw their dice, and the one with a larger number wins. What can be simpler, right? Somewhat counterintuitively, the game turns out to be not as simple as it looks. We will see some surprising properties of this game and will implement an optimal strategy for playing this game.
