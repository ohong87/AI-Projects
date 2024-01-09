# AI-Projects
Various AI / ML projects to practice my understanding as I continue to learn:

### Multilayer Perceptrons
Designed and trained multilayer perceptions (MLPs) to perform various classifications on a 2-Moon dataset and Iris dataset respectively. The 2-Moon model used a 2-d dataset and was 1 layer deep, while the Iris MLP was 2 layers deep. Results of both MLPs are plotted in a graph. 

### K-Means Clustering
Created a K-Means clustering algorithm to segment different pictures of elephants and dogs based on RGB values. Used a fully convolutional network (FCN) to extract features from original dog image and performed k-means clustering on the extracted features. Results are also graphed. 

### MRV + LCV Heuristics
Implemented minimum remaining values and least constraining values heuristics to solve a map coloring constraint satisfaction problem (CSP). The problem restrictions are that no two adjacent states share a color. There are only 3 colors (RGB) in the domain. The variables are the states of Australia.

### Simulated Annealing
Implemented the simulated annealing algorithm to solve the 8-queens problem (e.g. place 8 queens on an 8x8 chess board such that no queens attack each other). Experimented with different temperature, epochs, and decay ratio values as well.

### Value Iteration (Markov Decision Processes)
Implemented value iteration functions in the context of the Wumpus World problem (e.g. an agent must navigate a grid to get to a target while avoiding different 'threats'). Reaching the target rewards +10 points, landing on different threats are -5 and -10 points, and moving to a non-filled cell is -0.4 points. I experimented with different gamma, eta, and max_iter values to generate different grid output utilities. The Wumpus World is also provided. 
