# HarvardCS50-Week2-Scrabble

CS50's Introduction to Computer Science
Week 2, Lab 2

Project specifications:

"SCRABBLE

Background
In the game of Scrabble, players create words to score points, and the number of points is the sum of the point values of each letter in the word.

A = 1
B = 3
C = 3
D = 2
E = 1
F = 4
G = 2
H = 4
I = 1
J = 8
K = 5
L = 1
M = 3
N = 1
O = 1
P = 3
Q = 10
R = 1
S = 1
T = 1
U = 1
V = 4
W = 4
X = 8
Y = 4
Z = 10

For example, if we wanted to score the word Code, we would note that in general Scrabble rules, the C is worth 3 points, the o is worth 1 point, the d is worth 2 points, and the e is worth 1 point. Summing these, we get that Code is worth 3 + 1 + 2 + 1 = 7 points.

Implementation Details
Complete the implementation of scrabble.c, such that it determines the winner of a short scrabble-like game, where two players each enter their word, and the higher scoring player wins.

Notice that we’ve stored the point values of each letter of the alphabet in an integer array named POINTS.
For example, A or a is worth 1 point (represented by POINTS[0]), B or b is worth 3 points (represented by POINTS[1]), etc.
Notice that we’ve created a prototype for a helper function called compute_score() that takes a string as input and returns an int. Whenever we would like to assign point values to a particular word, we can call this function. Note that this prototype is required for C to know that compute_score() exists later in the program.
In main(), the program prompts the two players for their words using the get_string() function. These values are stored inside variables named word1 and word2.
In compute_score(), your program should compute, using the POINTS array, and return the score for the string argument. Characters that are not letters should be given zero points, and uppercase and lowercase letters should be given the same point values.
For example, ! is worth 0 points while A and a are both worth 1 point.
Though Scrabble rules normally require that a word be in the dictionary, no need to check for that in this problem!
In main(), your program should print, depending on the players’ scores, Player 1 wins!, Player 2 wins!, or Tie!."
