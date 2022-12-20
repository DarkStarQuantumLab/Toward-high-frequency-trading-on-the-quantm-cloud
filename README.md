# Implementing strategic games on quantum computers

*Quantum game theory* studies how strategic interactions, also referred to as strategic or non-cooperative games, can be improved upon when implemented using the emerging technology of quantum computers (a review of quantum game theory: https://link.springer.com/article/10.1007/s11128-018-2082-8). Non-cooperative games are ubiqituous, manifesting in biological settings when organisms compete over finite resources, in international relations when self-enforcing policies (like those for climate change) are to be drafted, in financial transactions, and in the desgin of supply-chain and network protocols. In all these settings, the fundamental solution of a non-cooperative game is the *Nash equilibrium*, a specific, stronger instance of multi-criteria optimization (MOO) in which each player's payoff in the game is the best possible, given the payoff of all other players. 

When non-cooperative games are played on a quantum computer, features of the quantum realm conspire to produce Nash equilibria (there can be more than one) that are better paying than those possible on a conventional computer (https://doi.org/10.1103/PhysRevLett.83.3077). This phenomenon holds real-world utility for online trading where the quantum computational implementation can produce better paying trades for the players. 

**A proposal for modeling and implementing high-frequency trading (HFT) as the strategic game Prisoner's Dilemma using cloud-based quantum processors appears in https://www.frontiersin.org/articles/10.3389/frai.2021.769392/full. The currenct version of this repo implements the first step: executing quantum Prisoner's Dilemma on IBM's quantum computer via Qiskit. The final version envisions culmination with a deployable HFT-on-quantum-cloud platfom.** 


On a related note, calculating Nash equilibrium can be computationally intensive for large games (many players with many strategies). To mitigate this, quantum computers can be used to accelarate its calculation. For example, see: https://github.com/DarkStarQuantumLab/NashEquilibrium. 

## How to run

1. In Google Collab through pip install qiskit (provided in the Notebook). The IBM Q account token may be required. 
2. Or upload the notebook to the IBM Quntum Lab (https://quantum-computing.ibm.com/). No installations are required, simply import required frameworks.
