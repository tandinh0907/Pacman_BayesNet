# Pacman_BayesNet
Welcome to the Ghostbuster Pacman project! This project utilizes Bayesian Networks to enhance the gameplay of Pacman, turning it into a challenging Ghostbusting adventure. The goal is to provide a more intelligent and strategic Pacman agent that can effectively navigate the maze and capture ghosts using probabilistic reasoning. 
# Introduction
In traditional Pacman, the game is mainly about avoiding ghosts and collecting pellets. This project takes it to the next level by introducing a Ghostbuster Pacman agent that uses Bayesian Networks to make informed decisions about when and where to chase ghosts. The Bayesian Networks model the uncertainty in the ghost locations and allow Pacman to make probabilistic predictions.
# Feature
Bayes Net: This is a representation of a probabilistic model as a directed acyclic graph and a set of conditional probability tables, one for each variable, as shown in lecture. The Traffic Bayes Net above is an example.
Factor: This stores a table of probabilities, although the sum of the entries in the table is not necessarily 1. A factor is of the general form $$f(X_1, ..., X_m, y_1, ..., y_n | Z_1, ..., Z_p, w_1, ..., w_q)$$. Recall that lower case variables have already been assigned. For each possible assignment of values to the $X_i$ and $Z_j$ variables, the factor stores a single number. The $Z_j$ and $w_k$ variables are said to be conditioned while the $X_i$ and $y_l$ variables are unconditioned.

Conditional Probability Table (CPT): This is a factor satisfying two properties:
1. Its entries must sum to 1 for each assignment of the conditional variables.
2. There is exactly one unconditioned variable.

# Usage
1. Run the GhostBuster Pacman agent: ```python busters.py -p GreedyBustersAgent```
2. Experiment with different Bayesian Network configurations by modifying the parameters in the bayesNet.py file.

# Contributing
Contributions are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.
