In this project, I manually implemented a Genetic Programming (GP) system to evolve a boolean expression fitting a given dataset.
The dataset included all possible input combinations for three boolean variables (A, B, C) and their corresponding correct outputs.

I started with a random population of expressions and evaluated their fitness based on how many correct outputs they produced.
Through selection, mutation, and evolution across generations, the system gradually improved.

Eventually, the evolved expression matched all dataset outputs perfectly.
The final discovered expression simplifies to:

(A AND (NOT B)) OR C.

I also plotted the fitness progression across generations, showing how the system evolved from an imperfect guess to an optimal solution.
