# Python Code Snippets for Discrete Mathematics Course

![specialization logo](notebooks/images/logo_specialization.png)

This repository contains Python code snippets from the [Discrete Mathematics for Computer Science specialization at Coursera](https://www.coursera.org/specializations/discrete-mathematics) and its [accompanying textbook](http://discrete-math.tilda.ws/). Together with interactive puzzles in the specialization, these interactive code snippets will give you a deeper understanding of the underlying ideas. To run them, you don't need to install or configure anything on your machine. Click the badge to invoke the notebooks in the cloud:
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alexanderskulikov/discrete-math-python-scripts/blob/master/notebooks/index.ipynb)

## Table of Contents

### Mathematical Thinking in Computer Science
![specialization logo](notebooks/images/logo_proofs.png)

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
