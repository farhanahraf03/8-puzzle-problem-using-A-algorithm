# 8-puzzle-problem-using-AStar-algorithm

8 puzzle problem is a problem in which a matrix of 3*3 comprising of numbers(1-8) and a blank state(0) ,
is maneuvered into a final/goal state of a different setup by moving the blank state in left/right/up/down direction.

Start State - 0 1 3         Goal State - 1 2 3
              4 2 5                      4 5 6
              7 8 6                      7 8 0




1)InitateAlgorithm - used to initate the algorithm
2)GraphBean - data srtucture used to store the graph and display it in string.
3)CreateGraph - creating and accepting the graph and also for initiating the AStar Algorithm
4)AStarAlgorithm - Used for finding the min o of steps used to reach goal nodes by determining:
                    g(n) = Distance from start node
                    h(n) = Heuristic distance i.e. total no of misplaced tiles at a given state
                    f(n) = h(n) + g(n)
                    
                   The state with the minimum f(n) value is considered to be the next state.
