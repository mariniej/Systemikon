# Systemikon/INTERACT
This folder contains code for the protein-protein interaction gene-pair annotation track.
# Introduction
The interact track uses protein interaction data to annotate the LoG with pairwise interactions
#Libraries
This function requires the iRefR package to be downloaded. There are three dependencies: igraph, graph, and RBGL. The igraph dependency is resolved by CRAN, but graph and RBGML come from BioConductor. 


```
source("http://bioconductor.org/biocLite.R")
	biocLite("graph")

source("http://bioconductor.org/biocLite.R")
	biocLite("RBGL")
```
# To Do
- [ ] Normalize confidence values between 0 and 1
- [ ] Write metadata to output
