# Report 

## Problem Option

    1. Air Cargo Problem 1
    2. Air Cargo Problem 2
    3. Air Cargo Problem 3

    1. breadth_first_search
    2. breadth_first_tree_search
    3. depth_first_graph_search
    4. depth_limited_search
    5. uniform_cost_search
    6. recursive_best_first_search h_1
    7. greedy_best_first_graph_search h_1
    8. astar_search h_1
    9. astar_search h_ignore_preconditions
    10. astar_search h_pg_levelsum

## Air Cargo Problem 1 breadth_first_search...

Expansions   Goal Tests   New Nodes
    43          56         180

Plan length: 6  Time elapsed in seconds: 0.04099738757230826
Load(C2, P2, JFK)
Load(C1, P1, SFO)
Fly(P2, JFK, SFO)
Unload(C2, P2, SFO)
Fly(P1, SFO, JFK)
Unload(C1, P1, JFK)

## Air Cargo Problem 1 breadth_first_tree_search.

Expansions   Goal Tests   New Nodes
   1458        1459        5960

Plan length: 6  Time elapsed in seconds: 1.2451433725197487
Load(C2, P2, JFK)
Load(C1, P1, SFO)
Fly(P2, JFK, SFO)
Unload(C2, P2, SFO)
Fly(P1, SFO, JFK)
Unload(C1, P1, JFK)

## Air Cargo Problem 1 depth_first_graph_search..

Expansions   Goal Tests   New Nodes
    12          13          48

Plan length: 12  Time elapsed in seconds: 0.0106391117745847
Fly(P1, SFO, JFK)
Fly(P2, JFK, SFO)
Load(C1, P2, SFO)
Fly(P2, SFO, JFK)
Fly(P1, JFK, SFO)
Unload(C1, P2, JFK)
Fly(P2, JFK, SFO)
Fly(P1, SFO, JFK)
Load(C2, P1, JFK)
Fly(P2, SFO, JFK)
Fly(P1, JFK, SFO)
Unload(C2, P1, SFO)

## Air Cargo Problem 1 depth_limited_search...

Expansions   Goal Tests   New Nodes
   101         271         414

Plan length: 50  Time elapsed in seconds: 0.11835417055420794
Load(C2, P2, JFK)
Load(C1, P1, SFO)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Unload(C2, P2, JFK)
Load(C2, P2, JFK)
Fly(P2, JFK, SFO)
Unload(C2, P2, SFO)
Fly(P1, SFO, JFK)
Unload(C1, P1, JFK)

## Air Cargo Problem 1 uniform_cost_search...

Expansions   Goal Tests   New Nodes
    55          57         224

Plan length: 6  Time elapsed in seconds: 0.0496323941033775
Load(C1, P1, SFO)
Load(C2, P2, JFK)
Fly(P1, SFO, JFK)
Fly(P2, JFK, SFO)
Unload(C1, P1, JFK)
Unload(C2, P2, SFO)

## Air Cargo Problem 1 recursive_best_first_search with h_1...

Expansions   Goal Tests   New Nodes
   4229        4230       17029

Plan length: 6  Time elapsed in seconds: 3.650816383653667
Load(C1, P1, SFO)
Load(C2, P2, JFK)
Fly(P2, JFK, SFO)
Unload(C2, P2, SFO)
Fly(P1, SFO, JFK)
Unload(C1, P1, JFK)


## Air Cargo Problem 1 greedy_best_first_graph_search with h_1...

Expansions   Goal Tests   New Nodes
    7           9           28

Plan length: 6  Time elapsed in seconds: 0.006545375380979657
Load(C1, P1, SFO)
Load(C2, P2, JFK)
Fly(P1, SFO, JFK)
Fly(P2, JFK, SFO)
Unload(C1, P1, JFK)
Unload(C2, P2, SFO)


