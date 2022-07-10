# Traveling-Salseman-Problem-Iran
The first ever TSP solution based on the coordinations of the cities in Iran, it is an exact solution to a point set of 1176 nodes.  
This is a project my classmate and I worked on for our Discrete Mathematics course. 
   
   

![map](https://github.com/Procedurally-Generated-Human/Traveling-Salseman-Problem-Iran/blob/main/White-Black.png)

## The Problem
Find the shortest circuit that goes through every city in Iran in which every node represents a city and the paths between two nodes are striaght lines. 

## Finding the Solution
To create this map, the following was needed:
- a dataset containing the coordinations of all cites in Iran
- a TSP solver algorithm
- sufficient computing power in order to find the solution in a reasonable time

## City Coordinates
We decided to use the following dataset: [Iran96-97](https://gist.github.com/alirezanet/0bbfb2921e421f8acb46244e0b5a8f8a).  
The dataset uses geographical coordinates, these needed to be converted to 2D x and y coordinates
After cleaning the data, 1176 cities remained (94.4% of 1245 cities).

## TSP Solver Algorithm
For the algorithm, we used Concorde, an exact TSP solver. for our project, we used [PyConcorde](https://github.com/jvkersch/pyconcorde) which is a Python wrapper around Concorde.

## Computing the Solution
The first attempt to compute the solution was attempted on my laptop After 2 days, the solution was still not found. We then switched to using Google collab, the solution was found in about 10 minutes.
