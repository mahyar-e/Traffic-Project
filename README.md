# Traffic-Project

Analysis of traffic evolution using percolation method.

![download](https://github.com/mahyar-e/Traffic-Project/assets/78594407/0368b254-632b-4b73-a9be-20f38266eb5a)

![download (1)](https://github.com/mahyar-e/Traffic-Project/assets/78594407/4318f345-095b-47ff-b1fb-364a7ed9f19b)

First, the critical parameter, p, is calculated for different sizes of grids. Then, the fractal dimension of the largest clusters for each size of lattices is calculated. But first we have to find the largest cluster.

This project is unfinished.



# Percolation & Fractal Dimension Simulation

This project explores percolation theory, cluster formation, and fractal analysis using Monte Carlo simulations. It generates random lattices, applies percolation thresholds, detects clusters, and analyzes their statistical and geometric properties.

### Features

- Random lattice generation (n × n grids)

- Site percolation with adjustable probability p

- Cluster detection via depth-first search (DFS)

- Extraction of the largest percolating cluster

- Ensemble simulations for statistical averaging

- Probability density estimation (KDE) & Gaussian smoothing

- Fractal dimension analysis with box-counting

- Visualizations using Matplotlib, PIL, and NetworkX


### Project Structure

- make_lattice(n) → generate random lattice

- change_lattice(lattice, p) → apply percolation threshold

- find_clusters(grid) → detect connected clusters

- percolation_with_ensemble(n, k=100) → run multiple simulations

- make_bool_largest_cluster(n, p) → isolate largest cluster

- box_counting_fractal_dimension(binary_array) → estimate fractal dimension


##### Inside the notebook, you can:

- Generate lattices of any size

- Vary percolation probability p

- Visualize clusters and percolating structures

- Estimate fractal dimension via box-counting



### Example Results

- Percolation threshold behavior as function of p
![download](https://github.com/mahyar-e/Traffic-Project/assets/78594407/0368b254-632b-4b73-a9be-20f38266eb5a)

- Cluster visualizations showing connected open site and argest cluster extraction highlighting percolation
![download (1)](https://github.com/mahyar-e/Traffic-Project/assets/78594407/4318f345-095b-47ff-b1fb-364a7ed9f19b)
