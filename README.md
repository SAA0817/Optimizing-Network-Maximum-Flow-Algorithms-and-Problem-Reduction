### Research on Optimization and Problem Reduction of Network Maximum Flow Algorithms

#### Abstract

    Solving the network maximum flow problem is a significant combinatorial optimization problem and a hot research topic in graph theory. We first provide the relevant symbols and definitions for the maximum flow problem, then summarize the previously proposed maximum flow algorithms and optimizations into two categories. We propose an improved method for the HLPP algorithm, test its performance, and evaluate its applicability. Finally, we introduce several types of problems that can be reduced to the maximum flow problem.
    
    In the maximum flow algorithm research section, we classify maximum flow algorithms into two categories based on their workflow characteristics: augmenting path algorithms and preflow-push algorithms. For augmenting path algorithms, we introduce classical methods represented by the EK algorithm and Dinic's algorithm and summarize their optimization strategies. Then, we introduce the MPM and ISAP algorithms, which are improvements based on Dinic's algorithm, and summarize their optimization methods. In the preflow-push algorithm section, we first summarize the characteristics and general templates of preflow-push algorithms, then focus on the Highest Label Preflow Push Algorithm (HLPP), which is widely recognized in academia as the most efficient method. We introduce two common optimization methods. At the end of the preflow-push section, we discuss and analyze the challenges of improving the HLPP algorithm's efficiency, namely the "ping-pong effect." We introduce and reproduce the Budget Algorithm, which effectively avoids the "ping-pong effect" (source code is not provided in the original paper), and compare the performance of the above algorithms using test data.

    At the end of the algorithm research, we summarize recent advances in network flow algorithms through several related papers. We learn from these papers about the existence of approximate linear-time complexity network flow algorithms and present future possible research directions for network flow algorithms.

    In the problem reduction section, we summarize four categories of problems that can be reduced to the maximum flow problem: bipartite graph maximum matching, minimum-cost maximum flow, bipartite graph maximum weight matching, and the minimum cut problem. We provide proof of correctness for the reduction and transformation of each type of problem.

    In this work, all content, including mainstream algorithm research and problem reduction, is implemented using C++ programs and tested with data. Finally, we include the program code in the appendix.

    Keywords: Network Maximum Flow; Dinic Algorithm; Highest Label Preflow Push Algorithm; Budget Algorithm



[full version](networkflow.pdf)
