###  QDBEA

Q-learning-guided Dual-branch Evolutionary Algorithm for Multi-objective Dual-Resource Constrained Flexible Job Shop Scheduling with Worker Fatigue


Introduction

Worker fatigue is an important factor affecting production efficiency, energy utilization, and human well-being in human-centric intelligent manufacturing. This paper investigates a multi-objective dual-resource constrained flexible job shop scheduling problem with worker fatigue (DRC-FJSP-WF), where operation sequencing, machine selection, and worker assignment are optimized simultaneously. A fatigue-aware scheduling model is established to minimize makespan, total energy consumption, and maximum worker fatigue. To solve this complex combinatorial optimization problem, a Q-learning-guided dual-branch evolutionary algorithm (QDBEA) is proposed, in which an adaptive search branch and a genetic search branch operate in parallel. A genetic branch explores the entire search space to maintain broad diversity, while a reinforcement learning branch focuses adaptively on the operation sequence layer, where the decision space is most challenging. Four heterogeneous operators are dynamically selected by Q-learning according to the population state, enabling responsive adjustment between exploration and exploitation. Computational experiments are conducted on extended Brandimarte benchmark instances. The results show that the QDBEA achieves competitive performance compared with several state-of-the-art algorithms in terms of objective values, inverted generational distance, and hypervolume. The findings confirm the effectiveness of the proposed method for fatigue-aware multi-objective scheduling in human-centric manufacturing systems.

### ISGA, Q-ISGA andQ-ISGA-D

Q-learning guided Improved Snow Geese Algorithm for Dynamic Scheduling, Q-ISGA-D

Q-ISGA-D, including ISGA, Q-ISGA, Tri-layer Encoding, POX Crossover, Mutation Operator, Levy Flight, and Targeted-Repair Operator.

Introduction

First, the corresponding scheduling environment of MO-DRC-FJSP and DMO-DRC-FJSP is established, which satisfies the constraints of the mathematical model.

Components

python == 3.9

numpy == 1.24.3

matplotlib == 3.5.0

pymoo == 0.6.0

Use

First deploy the project, configure the environment, and run main.py directly in your personal IDE.

How to see the results?

You can run the program to visualize the Gantt Chart and iterative curve after the end of the program.

