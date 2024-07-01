# Network Science Course - Final Project and Assignments

This repository contains the final project, project report, and four assignments from the Network Science course instructed by Santo Fortunato and his academic team. The course ran from June 3, 2024, for a duration of two weeks.

## Course Information

For more details about the course, visit the [course website](https://sites.google.com/view/netsci-course/home?authuser=0).

## Final Project

### Project Problem: Network Dynamics III - Opinion Dynamics

- **Task**: Generate a random network with 1000 nodes and link probability \( p = 0.01 \).
- **Initial Setup**: Assign binary opinions randomly to the nodes (about half with opinion 0 and the other half with opinion 1).
- **Hybrid Opinion Dynamic**:
  - The focal node takes the majority opinion of its neighbors with probability \( q \).
  - The focal node takes the opinion of a randomly chosen neighbor with probability \( 1 - q \).
- **Objective**: Test different \( q \)-values (\( q = 0, 0.1, 0.2, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0 \)).
- **Runs**: Perform 10 runs for each \( q \)-value, starting from an initial configuration with randomly distributed opinions.
- **Analysis**:
  - Compute the fraction of runs that lead to consensus for each \( q \)-value.
  - Plot the fraction of consensus runs as a function of \( q \).
  - If consensus is always reached for a \( q \)-value, compute the average number of iterations needed to converge.

