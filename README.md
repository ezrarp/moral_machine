# moral_machine
This is a final Project for COG415 at The University of Toronto.
This project uses the Moral Machine data set by Awad et al, 2018

# Project Motivation
Human ethical judgements are complex and nuanced

Primary goal: To develop a model that can simulate human moral judgments in ethical dilemmas

We want to capture the complex interplay of factors that influence moral decisions
Goals:
- Formalizing ethics computationally
- Understanding morality judgments, especially in ethical dilemmas, is crucial for fields like psychology, and philosophy
- AI Alignment
- Model how cognitive moral judgments are made
- How do we value and prioritize human life? → triage algorithms, automated weapons, self-driving cars

# Data Set
Used the Moral Machine Data set.

The input was the vector of the characters on each side of the scenario.

Used a random sample of 350,000 scenarios ~10% of the data set. 

# Model Architecture
5-layer Neural Network with an input cardinality of 20 and a binary output of [0, 1],
- Used the sigmoid activation function
- Used Mean Squared error as our loss function 
- Used SGD as an optimier

![alt text](image-1.png)


