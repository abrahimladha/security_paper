HYPOTHETICAL PROBLEMS CONCERNING THE THEORY OF RELATIVITY ON CRYPTOGRAPHIC CURRENCY IMPLEMENTATIONS
1. What is bitcoin?
    - history
        - satoshi nakamoto
        - circumstances to it being developed
    - units
        - BTC vs XBT and stuff
        - mention other small coins
    - ownership
        - how coins are "owned" by people
        - mention hacking and descrution
    - transactions
        - how are coins sent from a to b?
        - blockchain
        - double spending problem
        - forking of the network with historic examples 
    - mining
        - how people are gonna verify transactions
        - miners fees
        - pool mining
        - proof of work vs proof of stake 
        - submitting shares
        - block size, block standard
        - just go over the entire specification
2. Theory of Relativity
    - history
        - Einstein and lorentz
        - talk about how weird it is
    - Posulates and formalism
    - lorentz equations
        - for time
        - for distance
        - graph of energy vs speed (asymtotic to c)
    - time travel
        - just something short proving someone can come back to the future
    - lizard problem
        - showing two events would be independent (spoiler alert)
3. Some example scenarios
    - pool mining of 2 nodes
        - earth and mars example where is the center?
        - picture of the two
    - pool mining of 3 nodes
        - just generalize what the center is
        - complete graph vs path vs star vs cycle 
    - finite lattice of evenly spaced miners
        - basically a generalization from 3 to n nodes.
        - complete graph is expensive. connectivity of 8ish in modern usages
4. Cases of a fixed blocktime
    - how we derive a graph structure 
    - why the lattice works so well in theory
    - planetary orbits
        - 4 cases of orbital paths
        - do cases as functions of relativistic speed and distances
            - contained rings (planetary)
            - overlapping (comets)
            - disjoint (distant solar systems)
            - spiraling (earth with some n satellites)
    - linearly accelerating miners (rockets)
        - proof linearity implies only two cases
        - small diagram
        - case 1 moving away from each other
        - case 2 moving towards each other
            - consider when this case decomposes back into case 1 
5. Cases of a variable block time
    - why a variable block time per user doesn't make any sense
    - avoidance of the probabilistic blocktime attack that effected dogecoin
    - proportional to some param of the graph
        - speed of >50% of the centroid of the graph
            - but which 50% how is it determined?
        - speed of largest individual node
        - measures of graph connectivity, girth, toughness
            - decomposing a graph 
            - humanistic tendency of pool mining for a star graph
6.Propogation and arguments against arbitrary unlimited growth
    - keeping the network on the same blockchain
        - large arbitrary graph 
        - two nodes transact coins so nearby peers must be updated
        - their peers and their peers must be updated
        - time until next transaction is shortest time from farthest nodes
        - significant delay until next transaction can take place
7. Extras
    - mining security in thermodynamics
        - some nice statistics
        - "by 3016, it will take 3 times the sons energy to mine a block" etc
    - Quantum computers effect on mining
        - mining when some nodes compute faster than others
        - growth size of the blockchain (in terrabytes)
            - dealt with in nakamotos original paper
    - information loss due to black holes
        - relativistic effects of data that escapes a BH.
        - total information loss
8. Sources and citations
    - like 60 so far will list out eventually

            
