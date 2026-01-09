# Text Generation with Markov Chains

## Overview
This project implements a simple text generation algorithm using Markov Chains in Python.  
The model predicts the next word based on the previous word using probabilistic transitions learned from training text.

---

## Objective
To build a statistical model that generates text by predicting the probability of a word based on the previous word, following the Markov property.

---

## What is a Markov Chain?
A Markov Chain is a stochastic process where the next state depends only on the current state and not on the sequence of previous states.

In this project:
- State = Current word  
- Transition = Probability of the next word  

---

## Technologies Used
- Python 3
- random
- collections.defaultdict

---

## Training Data
The model is trained using domain-specific text related to data science, analytics, and machine learning to produce meaningful text output.

---

## How It Works
1. Input text is converted into lowercase words
2. A Markov Chain is created by mapping each word to possible next words
3. Text generation starts from a given seed word
4. The next word is selected randomly from learned transitions
5. The process continues until the required length is reached

---


Note: Output varies each time due to randomness.

---

## Key Features
- Simple implementation of Markov Chains
- Word-level text generation
- Probabilistic text output
- Beginner-friendly NLP project

---

## Learning Outcome
This project helped in understanding:
- Markov Chains in Natural Language Processing
- Probabilistic modeling
- Text generation using Python

---

## Author
Yasmeen Rafique


