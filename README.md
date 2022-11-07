# Mehbooba_Sokoban

Reddy is currently working on the base game. 
Meanwhile we have to think of how we could implement either :
    1. BFS
    2. DFS
    3. IDS 
    4. A* search
    5. Any other search algo sir has taught
within this environment. 
We will have multiple start states and multiple goal states
we have to make sure that the goal state of one block/crate doesn't end up creating deadlock for another crate

Algo should work this way (outline) :
 step 1 : find shortest path between crate and crate_slot 
 step 2 : remember this path, now we have to figure out a way to move our worker along this path, staying behind the crate at all times. 
 
