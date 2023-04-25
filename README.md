# DC-DP-means-algorithm-in-python
Implement the non parametric DC-DP means algorithm and its parallel version PDC-DP means from the research paper "Revisiting DP-means: Fast Scalable Algorithms via Parallelsim and Delayed Cluster Creation"
https://proceedings.mlr.press/v180/dinari22b/dinari22b.pdf

Test the algorithm on synthetic 2D data of N = 1000 points genereated from K isotropic gaussians. Demostrate how different random initializations yield different results. Demostrate the effect of changing values of ƛ.

Also, test the algorithm on rgb values of a mandril image and display the results by replacing color of each pixel with the value of centroid of cluster the pixel was assigned to.
