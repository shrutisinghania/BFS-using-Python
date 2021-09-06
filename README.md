# Breadth-First Search using Python


A breadth-first search algorithm follows multiple directions at the same time, taking one step in each possible direction before taking the second step in each direction. 
In this case, the frontier is managed as a queue data structure. The catchphrase for BFS is “first-in first-out.” In this case, all the new nodes add up in line, and nodes are being considered based on which one was added first (first come first served!). This results in a search algorithm that takes one step in each possible direction before taking a second step in any one direction.

(An example: suppose you are in a situation where you are looking for your keys. In this case, if you start with your pants, you will look in your right pocket. After this, instead of looking at your left pocket, you will take a look in one drawer. Then on the table. And so on, in every location you can think of. Only after you will have exhausted all the locations will you go back to your pants and search in the next pocket.)

## Pros:
    This algorithm is guaranteed to find the optimal solution.
## Cons:
    This algorithm is almost guaranteed to take longer than the minimal time to run.
    At worst, this algorithm takes the longest possible time to run.