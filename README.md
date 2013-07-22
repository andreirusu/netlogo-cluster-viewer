netlogo-cluster-viewer
======================

This NetLogo 3D model can be used to view data clusters in 3D renderings of datasets and arbitrary latent representations. 

## Requirements
* Netlogo (3D): free to download at http://ccl.northwestern.edu/netlogo/


# Current features: 
* reads a file line-by-line and displays points; each line should containt: CLASS X Y Z, where:
  * CLASS: is a positive integer encoding  a class label, or -1 for n/a.
  * X, Y, Z: are coordinats in 3D space.
* partitioning of input space (only a cube is displayed)
  * the cube's center can be dynamically adjusted
  * the size of the cube can also be adjusted dynamically


# Planned features: 
* support for arbitrarily many input points 
* dynamic zoom in/out
* reporting distances in various metrics
* Voronoi tessellation
* dbscan clustering
* support for higher-dimensional inputs via Barnes-Hut-SNE
* communication between simulations of various partitions
