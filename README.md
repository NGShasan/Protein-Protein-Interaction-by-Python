## Protein-Protein-Interaction-by-Python

We used networkx for analysing the interaction between Inferred Links of high-throughput protein-protein interactions. 

NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
The more details about networkx can can be found here, https://networkx.github.io/documentation/stable/index.html.

### Dataset:
https://www.inetbio.org/wormnet/downloadnetwork.php

+ Data Type: DM-HT	
+ Organism: fly(D.melanogaster)	
+ Links: 4660	
+ Description: Inferred Links by high-throughput protein-protein interactions

### Implementation:
1. Build the corresponding network (G) with Networkx   
2. Find number of nodes, number of edges and the average degree of the network
3. Find the density of the network.
4. Find the minimum spanning tree in G and draw it.
5. Draw the degree distribution histogram.
6. Find the largest connected component of the network  (LC) and implement the tasks:
       
     i. Draw LC.
       
     ii. Find its diameter
     
     iii. Find  center of LC
     
     iv. Find the number of clique communities with 3 nodes.
     
     v. Find the protein that chnage in its status has potentially the biggest effect on the rest of the network
