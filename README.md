# RPSLS
Rock-paper-scissors-lizard-Spock (RPSLS) is a variant of Rock-paper-scissors that allows five choices. Each choice wins against two other choices, loses against two other choices and ties against itself. 

Here we build a Python function rpsls(name) that takes as input the string name, which is one of "rock", "paper", "scissors", "lizard", or "Spock". The function then simulates playing a round of Rock-paper-scissors-lizard-Spock by generating its own random choice from these alternatives and then determining the winner using a simple rule.
While Rock-paper-scissor-lizard-Spock has a set of ten rules that logically determine who wins a round of RPSLS, coding up these rules would require a large number (5x5=25) of if/elif/else clauses in this project. A simpler method for determining the winner is to assign each of the five choices a number:

0 — rock
1 — Spock
2 — paper
3 — lizard
4 — scissors
In this expanded list, each choice wins against the preceding two choices and loses against the following two choices (if rock and scissors are thought of as being adjacent using modular arithmetic).
