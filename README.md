# Dissertation

This repo contains the code for my dissertation and the dissertation report. 

## Purpose

Network analysis often considers the cost of a journey in terms of its price or distance. However, different users will have different needs and so different objectives. This is the case for commuters and leisure cyclists - who both need serving as we look to increase active travel in urban spaces. The biobjective analysis contained here analyses a network for how preferential it is for these two users.

## A breakdown of the code is as follows:

- The code allows for the reading of a urban network from Open Street Map
- Edges are assigned weighted 'discomfort' values according to the edge type e.g. cycle lane, primary road, residential road. Safety is used for discomfort here but can be changed easily in the code.
- The user can choose the number of shortest paths to be found between MOSA nodes (500 recommended)
- Total lengths and discomfort values are found for each path and normalised
- Data is outputted as a csv file which can be used to produce Pareto fronts.
- '2.3 A Biobjective Network Analysis' explains the theory and reading of Pareto fronts to look at how each user is served
