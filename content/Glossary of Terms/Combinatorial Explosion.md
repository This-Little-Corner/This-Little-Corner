“Combinatorial explosion” refers to the manner in which a relatively small number of elements can be recombined with each other in sufficiently numerous ways such that it is often impossible to consider each possible combination individually. This is part of why computation is not sufficient for explaining intelligent problem-solving.

For a detailed explication of this concept in context of AI problem solving, see “Relevance Realization and the emerging framework in cognitive science” (Vervaeke, Lillicrap, Richards, 2012), under the heading “Relevance Realization and Problem Solving)
The initial coinage of the term “combinatorial explosion” goes back to Keith J. Hollyoak (1995) in chapter 8 of “Problem Solving”.

Newell and Simon’s General Problem Solver model (GPS) posits an initial state, a goal state, a set of operators which an agent can use to transform one state into another, and a set of path constraints which disallow certain types of solutions. These elements generate a problem space or search space consisting of all the possible sequences of states that the agent can take from the initial state to the goal state while obeying path constraints.

The formula for the number of possible sequences in the search space may be expressed by the formula F^D, where F is the number of operators and D is the number of discrete possible states.

The Chess Example:
In an average game of chess, 30 moves are possible per turn, and games typically take 60 turns. The corresponding search space for the typical chess therefore consists of 30^60 possibilities. This number is far too large for any conceivable computer to consider algorithmically. For comparison, the estimated number of electrons in the universe has been estimated at 10^79.

Related: Newell and Simon’s General Problem Solver (GPS), ill-defined vs Well-defined problems, algorithmically, heuristics, the finitary predicament, relevance-realization