Efficient Processing of Mutation Sequences Based on Aihara’s Algorithm
Abstract

This project investigates the application of Aihara’s algorithm for efficient processing of mutation sequences. The algorithm is designed to minimize redundant computations by incrementally updating only the components affected by each mutation, thereby achieving improved time complexity compared to naive recomputation strategies.

Research Motivation

In many computational settings, sequences of mutations require repeated updates to an underlying structure. Performing a full recomputation after each mutation is inefficient and does not scale well. This project explores an algorithmic approach that preserves correctness while significantly improving computational efficiency.

Methodology

The project is based on the algorithm proposed by Aihara and is implemented in Python following the formal description in the original research article. The implementation leverages dependencies between consecutive mutations to perform localized updates. A comparative analysis with an alternative algorithm is conducted to evaluate performance differences.

Analysis and Evaluation

The algorithms are evaluated with respect to runtime behavior and theoretical time complexity. The results demonstrate that Aihara’s algorithm provides a more scalable solution for handling long sequences of mutations.

Technologies

Python
Jupyter Notebook

The Article- [10093210v3_241215_101132 (3).pdf](https://github.com/user-attachments/files/24395393/10093210v3_241215_101132.3.pdf)

Author
Or Loren
אי
