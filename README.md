# rudy-g05-graphs-5to50nodes

This repository contains unweighted graph instances generated with the [Rudy graph generator](https://biqmac.aau.at/biqmaclib.html), using an edge probability of 0.5. The dataset covers graphs with N = 5, 10, 20, 30, 40, and 50 nodes.

This dataset was used in the preprint:  
**"How to Incorporate External Fields in Analog Ising Machines"**  
[arXiv:2505.08796](https://arxiv.org/pdf/2505.08796)

## File Format

Each graph is stored as a plain text file using the Rudy export format. The file starts with two integers on the first line:

N E

- `N` is the number of nodes  
- `E` is the number of edges

The following `E` lines each describe one edge:

u v w

- `u` and `v` are the endpoints of the edge (with node indices ranging from 1 to N)  
- `w` is the edge weight (always 1 in this collection)
