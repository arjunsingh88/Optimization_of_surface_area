# Optimization of surfacearea
The goal of the project was to build an approximation algorithm for finding the house(rectangle) with largest surface area inside a plot of land(non-convex polygon). Exploration of solution using two heuristic's approach   ----- 1.Taboo Search   ------ 2.Particle Swarm Optimization

A Heuristics problem to build an approximation algorithm for finding the largest rectangle inside a non-convex polygon.

The components of the problem are: 
* The polygon: the constrained search space; 
* The rectangle: the solution of the problem; 
* Feasibility (is the rectangle inscribed in the polygon?): A constrained problem; 
* The area of the rectangle: the evaluation function; 
* Problem of maximization.. 
  * In this case we maximize the Area
  * To maximize Area we optimize two points or 4 coordinates and an angle for rotation


The performance of all heuristic algorithms influenced by the search space structure. Consequently, the design of an efficient algorithm needs to exploit, implicitly or explicitly, some features of the search space. For many heuristics, especially local searches, the complexity of the algorithm is very strongly influenced by the asperity of the local structures of local optima

# Algorithms
|Taboo Search|Particle Swarm Optimisation|
|---|---|
|The main objective of the algorithm is to discourage the search process from visiting configurations in some space regions that are already considered as explored.|The PSO algorithm employs a swarm of particles, which traverse a multidimensional search space to seek out optima. Each particle is a potential solution and is influenced by experiences of its neighbors as well as itself.|

 
|Polygon|Shape|
|:---:|:---:|
|`Polygon 1`:<br> ((10,10),(10,400),(400,400),(400,10))|![h1](https://user-images.githubusercontent.com/45566835/83153548-62a05200-a0ff-11ea-9fcf-3d57066627f8.png)|
|`Polygon 2`:<br> ((10,10),(10,300),(250,300),(350,130),(200,10))|![h2](https://user-images.githubusercontent.com/45566835/83153550-6338e880-a0ff-11ea-8177-6aa715b8401f.png)|
|`Polygon 3`:<br> ((50,150),(200,50), (350,150),(350,300), (250,300),(200,250), (150,350), (100,250), (100,200))|![h3](https://user-images.githubusercontent.com/45566835/83153553-6338e880-a0ff-11ea-8617-00f9a0d5feb8.png)|
|`Polygon 4`:<br> ((50,50),(50,400),(220,310),(220,170),(330,170),(330,480),(450,480),(450,50))|![h4](https://user-images.githubusercontent.com/45566835/83153555-6338e880-a0ff-11ea-8b29-3bd2c57d9898.png)|
