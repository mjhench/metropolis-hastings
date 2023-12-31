# Metropolis-Hastings Algorithm
This code for the Metropolis-Hastings algorithm I made as part of a final project for one of my courses. In it, I used Python to implement the Metropolis-Hastings algorithm (a Markov chain Monte Carlo method) to sample the posterior distribution of a noisy exponentially-decaying data signal and find the original data signal parameters. The data was of the form f(t) = a * exp(-b * t) + noise, with a and b sampled randomly on the interval [0, 1) and the noise being sampled from a normal distribution with mean = 0 and variance = 0.01. Barring some portions of the code that were taken from course material on the class webpage and which have been explicitly noted in the Python notebook, the code is entirely my own.

Running this code requires installation of the Jupyter environment. This can be done as either a standalone installation or through an IDE such as PyCharm Professional or DataSpell.

Note: I received permission from the course professor to post this code on GitHub.
