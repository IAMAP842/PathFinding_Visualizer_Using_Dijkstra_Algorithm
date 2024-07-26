# PathFinding_Visualizer_Using_Dijkstra_Algorithm
This pathfinding visualizer utilizes Dijkstra's algorithm to determine the shortest path between a source and a destination node. Users have the ability to customize paths by selecting the start and end nodes, as well as adding blocks or weights to nodes, thereby affecting the optimal path.





# Dijkstra's Algorithm

<!-- - Picks the unvisited vertex with the lowest distance.
- calculates the distance through it to each unvisited neighbor,
  and updates the neighbor's distance if smaller and repeat this until we visited all nodes. -->

Dijkstra's Algorithm works by identifying the shortest paths between a starting node and all other nodes within a graph.

The algorithm maintains a record of the shortest known distances from each node to the source node, updating these records whenever a shorter route is discovered. Once the algorithm determines the shortest path from the source node to another node, that node is marked as "visited" and included in the final path. This process continues until all nodes have been visited, ensuring that the shortest routes from the source node to every other node are identified.

The reliability of Dijkstra's algorithm in finding the shortest paths stems from its greedy strategy. It always selects the node with the smallest known distance to explore next, updating the distances to its neighboring nodes if a shorter path is found. By processing nodes in the order of increasing distance, the algorithm ensures that the shortest path to each node is established before moving on to more distant nodes.


## Tech Stack Used

### ReactJS
1. Virtual DOM: ReactJS leverages a virtual DOM to enhance user interface performance. By keeping a lightweight in-memory version of the actual DOM, React can efficiently manage updates and reduce unnecessary re-renders, resulting in better performance and a more seamless user experience.

2. Extensive Ecosystem and Community Support: ReactJS boasts a rich ecosystem supported by an active community. Developers have access to a wide array of resources, libraries, and tools, offering numerous solutions to common development problems.

### Vercel

The app is hosted on Vercel, which offers several key benefits:

1. Optimized Performance and Global CDN:
   Vercel leverages a globally distributed Content Delivery Network (CDN) to deliver web content quickly and efficiently to users worldwide. By caching content at edge locations, Vercel ensures faster load times and reduced latency, resulting in a smoother and more responsive user experience.

2. Seamless Deployment and Integration:
   Vercel offers seamless integration with popular version control systems like GitHub, GitLab, and Bitbucket. This integration allows for effortless deployment of applications with automatic builds and previews. Developers can easily push updates and collaborate on projects, streamlining the development workflow.

3. Serverless Functions and Scalability:
   Vercel supports serverless functions, enabling developers to build scalable and performant back-end services without managing servers. These functions auto-scale based on demand, ensuring that applications can handle varying traffic loads efficiently. This scalability is ideal for modern web applications that need to grow dynamically with user demand.

Also this project required knowledge of Dijkstra's Algorithm in detail.
