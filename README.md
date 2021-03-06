# QMatch: The Quantum version of your favorite dating app

## Abstract
QMatch is a matchingmaking app that relys on quantum principles (VQE) for matching Quantum Computing Engineers/Scientists with the scientists of their dreams. The questions used for assessing compatibility are directly linked to a random matrix for which users must obtain an accurate enough approximation to match with a profile with the desired attributes. 

## Introduction
With more than 1500 dating apps having been created to date, it is clear that online matchmaking is a huge market with an expansive and diverse user base. For anyone who has used one of these applications, it is clear that there is some ingredient missing in the matchmaking algorithms. That missing ingredient is *Quantum Mechanics*. With QMatch, we utilize the power of quantum computing and quantum/classical algorithms to help you find your true *entangled pair*.

Quantum Computing (QC) is the paradigm that uses Quantum properties applied to computations in order to accelerate them. Among the various algorithms and applications of QC, Varational-Quantum-Eigensolver (VQE) is a quantum/classical hybrid algorithm for estimating the lower and upper bounds from a certain matrix $H$ (the Hamiltonian of the system).


## Basic Principles
In this project, we propose a matchmaking application where each of the questions asked to the user are assigned a random matrix $H$ for which you have to create an ansatz to approximate its ground state. We arrange for an error bound to decide whether the estimation is good or bad.

## Motivation/goals
Our motivation was to give a "quantum spin" to an already popular dating app. Our focus was on using the VQE as a metaphorical approach to select "yes" or "no" to certain personality criteria while implementing an interactive platform to learn about constructing effective ansatzes. If your approximation is within a margin of error relative to the ground state of the matrix of that attribute, then you succesfully select that attribute. Thus, after several approximations (selection criteria), users will have matched with a quantum engineer they are compatible with. Here, famous physicists serve as placeholders for what could be real user profiles of those in the quantum community. 

Our goal is to introduce users to the VQE algorithm by letting them propose simple ansatzs by selecting parameters/angle which approximates the ground state of the system. With practice, users should be able to improve their ability to choose ansatz with higher fidelity. 

## Proposals for future work

 * Implement the game with better graphics.
 * Use real profiles by multiple users that play the game (databases).
 * Introduce a swiping mechanic.
 * Adding parametrized games to implement an easier mode
 * Implement more questions.
 * Utilize more qubits and increase ansatz complexity for more advanced users. 

## How to run this game

Just run main_new.py and enjoy the fun!

## Instructions/Flow
 The overall flow of the game is:

  1. Start the game.
  2. Answer each question by proposing an ansatz and its parameters.
  3. If your VQE approximation is good enough, you'll be answering "Yes".
  4. After completing 3 questions, the scientist of your dreams will be paired with you.
  5. Repeat cycle or exit the game.
