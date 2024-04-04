# Understanding the Concepts


## Network Types
**Scale-free:** Networks where node degree distribution follows a power law (e.g., think popular people on social media with many connections, and most people with few connections).

**Broad-scale:** Networks that have a degree distribution broader than a Poisson distribution, but not strictly a power law.

**Random geometric:** Networks where nodes are placed in a space, and links exist if nodes are within a certain distance.

**Network Resilience:** The ability of a network to maintain functionality when nodes or links fail.

## Attack Strategies
**Random Attack:** Removal of nodes or links without specific targeting.

**Targeted Attack (Degree-Based):** Removal of nodes with the highest degree (most connections) first.
Using the Mortia Network Generator


## Network Metrics

The key part of the project is measuring how the different network types respond to attacks. Here are some metrics to consider:

**Average degree of the network:** Calculate the average degree of the network. Does this value increase significantly in certain networks?

**Largest Connected Component:** Track the size of the largest remaining connected group of nodes after an attack. A resilient network would maintain a large connected component.

**Average Path Length:** Calculate the average shortest distance between pairs of nodes. After an attack, does this value increase significantly in certain networks?

**Average Clustering coefficient**: Calculate the average clustering coefficient of the network. Does this value increase significantly in certain networks?

**Network Efficiency:** A measure of how effectively information flows through the network. Look for changes in efficiency under attacks.
Steps for the Student


## Experiment
Generate multiple networks of each type (scale-free, broad-scale, random geometric) with varying sizes or parameters (i.e. $N$ = 100, 200, 500 and 1000). In all cases use the same average degree (i.e. $k_{avg} = 5$)


Systematically apply random and targeted attacks, incrementally increasing the number of removed nodes.
For each attack compute the network integrity measures. 

**Analyze and Visualize:** Compare how the different network types respond under each attack strategy. Create plots to visualize the changes in the resilience metrics. 


**Network Size and Complexity:** How does the number of nodes or density of connections affect resilience?
Other Attack Strategies: Could attacks based on other centrality measures (e.g., betweenness centrality) be explored?
Literature Review: Encourage the student to read research papers on network resilience for inspiration and deeper understanding.

## Project Goals

1. Generate Networks

2. Simulate Attacks

3. Monitor key network metrics

4. Compare network resilience under different attack strategies

5. Visualize the results