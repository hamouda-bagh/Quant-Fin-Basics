# Quant-Fin-Basics
My personal work on the numerical projects of a book called **"A First Course in Stochastic Calculus"**.

The book is newly published by Louis-Pierre Arguin, an assoicate professor of mathematics at Brauch College & Graduate Center CUNY. It covers the basics of the stochastic calculus used in the Quantitative Finance domain, form Brownian Motion to Itô calculus.

The general objective of the book is to present the theory of Itô calculus based on Brownian motion and Gaussian processes. In particular, the goal is to construct stochastic processes using the Itô integral and to study their properties. The last chapter presents the applications of the theory to option pricing in finance.

Here you will find my personal codes written for each chapter in a separate file.

The link to the book on Amazon is the following : https://www.amazon.com/Course-Stochastic-Calculus-Applied-Undergraduate/dp/1470464888

## Contents

### Chapter 1 Basic Notions of Probability

It reviews the elementary notions of probability theory needed along the way. This offers sufficient opportunity to get acquainted with basic commands in Python.

### Chapter 2 Gaussian Processes

The chapter introduces the notion of Gaussian processes, based on the notion of Gaussian vectors. This is where we learn the Cholesky decomposition to express jointly Gaussian random variables in terms of IID standard Gaussians. This concept is very useful to numerically sample a plethora of Gaussian processes, such as Brownian motion, the Ornstein-Uhlenbeck process, and fractional Brownian motion.

### Chapter 3 Properties of Brownian Motion

This chapter studies the properties of Brownian motion in more detail. In particular it introduces the notion of quadratic variation that is central to Itô calculus. The Poisson process is also presented as a point of comparison with Brownian motion.

### Chapter 4 Martingales

The class of stochastic processes known as martingales is introduced here. It is built on the conditional expectation, which is defined as a projection in the space of random variables with finite variance. Elementary martingales, such as geometric Brownian motion, are given as examples. One of the powers of Itô calculus is to give a systematic way to construct martingales using Brownian motion. Martingales are useful, as some probabilistic computations are simplified in this framework. For example, solving the gambler’s ruin problem using martingales is illustrated.

### Chapter 5 Itô Calculus

The Itô integral is constructed as a limit of a martingale transform of Brownian motion. The martingale transform is analogous to Riemann sums in standard calculus. Itô’s formula, which can be seen as the fundamental theorem of Itô calculus, is also numerically verified. This is where we start to explore the beautiful interplay between partial differential equations (PDE) and stochastic processes.

### Chapter 6 Multivariate Itô Calculus

### Chapter 7 Itô Processes and Stochastic Differential Equations

### Chapter 8 The Markov Property

### Chapter 9 Change of Probability

### Chapter 10 Applications to Mathematical Finance
