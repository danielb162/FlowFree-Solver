# FlowFree-HeuristicAlgo
Java algorithm to solve puzzles from the free game "Flow Free" on the App Store and Google Play.

This is done using closest distance of the pair of likewise colored points as a heuristic to begin a Dijstra-driven approach to finding a viable path. Furthermore, backtracking is implemented in case a previously chosen path 'traps' a point through one of its actions; trapping would involve making a move/path which would prevent a dissimilarly colored point from having a viable path to its pair, i.e. if the algorithm taking an action would lead to an unsolvable scenario.