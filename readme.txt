This repo contains code that verifies weather the given input graph is Eulerian or not and finds the Euler tour of the graph if exists with a better graph traversal implementation, to increase
the performance by 6s for considerably large input graph with over 10000 nodes and 20000 edges.


1. Euler.java has  findTours(), stitchTour() methods implemented and called through the findEulerTour() method.
2. LP2.java is the driver program from where the graph is input and methods of Euler.java are called. If the graph is Eulerian the subtours are found and stitched together, then time taken for finding the Euler tour is printed to the console.
