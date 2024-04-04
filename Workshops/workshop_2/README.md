It´s wanted to obtain the shortest paths to ship some products, however, this is very similar 
to what TSP is, and to solve this problem you can use Ant Colony Optimization (ACO).
TSP is about a salesman must visit a set of cities exactly once and return to the original city, 
thus finding the shortest routes.
To go deeper into this algorithm, it is about a given number of ants that make multi-point 
foraging trips and at the same time look for the shortest routes to accomplish their goal. The 
ants are influenced by two factors, alpha (which determines the extent to which the ants are 
influenced by pheromone traces left by other ants) and beta (which determines the extent to 
which the ants are influenced by the distance to be traveled). It must be taken into account 
that the pheromone has a certain intentionality and can evaporate along the way. The ants 
start having a random behavior but then the probabilities that a path will be traveled by an 
ant are found by the factors mentioned above, resulting in a pattern of travel and thus find 
the best routes. The cities and the routes have to be plotted in 3D
