# PathFinding_Visualizer_Using_Dijkstra_Algorithm
This pathfinding visualizer utilizes Dijkstra's algorithm to determine the shortest path between a source and a destination node. Users have the ability to customize paths by selecting the start and end nodes, as well as adding blocks or weights to nodes, thereby affecting the optimal path.





# Dijkstra's algorithm

<!-- - Picks the unvisited vertex with the lowest distance.
- calculates the distance through it to each unvisited neighbor,
  and updates the neighbor's distance if smaller and repeat this until we visited all nodes. -->

Dijkstra's Algorithm works by identifying the shortest paths between a starting node and all other nodes within a graph.

The algorithm maintains a record of the shortest known distances from each node to the source node, updating these records whenever a shorter route is discovered. Once the algorithm determines the shortest path from the source node to another node, that node is marked as "visited" and included in the final path. This process continues until all nodes have been visited, ensuring that the shortest routes from the source node to every other node are identified.

The reliability of Dijkstra's algorithm in finding the shortest paths stems from its greedy strategy. It always selects the node with the smallest known distance to explore next, updating the distances to its neighboring nodes if a shorter path is found. By processing nodes in the order of increasing distance, the algorithm ensures that the shortest path to each node is established before moving on to more distant nodes.

## Tech Stack Used

### ReactJs

1. Virtual DOM: Virtual DOM: ReactJS utilizes a virtual DOM (Document Object Model) to efficiently update and render user interfaces. By maintaining a lightweight representation of the actual DOM in memory, React can perform efficient updates and minimize unnecessary re-renders. This results in improved performance and a smoother user experience.
2. Rich Ecosystem and Community Support: ReactJS has a vibrant and active community with extensive resources, libraries, and tools available. This ecosystem provides a wide range of solutions for common development challenges.

### Cloudflare

Hosted front end on Cloudflare. It offers certain advantages.

1. Content Delivery Network (CDN):A CDN is a geographically distributed group of servers that caches content close to end users this improves visitors experience faster page loading times.
2. Easy Deployment and Continuous Integration: Cloudflare Pages offers seamless integration with popular version control systems such as GitHub. This allows for easy deployment of frontend updates through automated pipelines, ensuring a smooth and efficient development workflow.
3. Cost-effective Solution: Cloudflare Pages offers a generous free tier for hosting static websites and provides cost-effective pricing plans for higher traffic volumes.

## Screenshots

<img src="./screenshots/Tutorial.png" height="600">
<img src="./screenshots/first.png" height="600">
<img src="./screenshots/blocked.png" height="600">
<img src="./screenshots/weight.png" height="600">
<img src="./screenshots/path.png" height="600">
