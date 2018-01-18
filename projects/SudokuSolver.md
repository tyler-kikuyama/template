---
layout: project
type: project
image: images/SudokuProject.png
title: Sudoku Solver
permalink: 
# All dates must be YYYY-MM-DD format!
date: 2017-03-15
labels:
  - Java
  
  
summary: An assignment I completed in my ICS 211 class. It is a program that can solve a sudoku problem.
---

Sudoku is a game where a larger square is filled with smaller squares that contain numbers. The numbers in the smaller squares must be arranged so that each row, column, and smaller square area within the main square contain numbers from 1 to the length of the row/column/side of square. However, there can be no repeats in the sequence of numbers. The game starts off with a few of the numbers already present in the large square and the player must fill in the remaining blank squares while following the rules.
  The assignment was to create an algorithm that could take in a sudoku problem and fill in all of the blanks with the correct numbers. It took me about a week to solve with aid from my professor and TA. A lot of code was already provided to help with the tests and some of the functions were already created by the professor in advance so I wrote the code for a recursive sudoku solver function and also a function that made sure that all the values in a given box were correct. Recursion was used to call back a function that would check if a given number could work for a cell. Another function checked all the possible numbers that could fit in a cell and the recursive function would go through all the possible values until it found one that fit for all the cases. 



