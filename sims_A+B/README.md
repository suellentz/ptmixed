# Code for simulations A and B

Before running these simulations, create the following subdirectories in your working directory:
- data
- results
- results/gathered

Each simulation comprises 4 scripts that should be run sequentially:
- the first generates the data (5000 repetitions for each combination of power parameter and sample size)
- the second estimates the mixed models (here, computing the 5000 repetitions may be time consuming - the code provided can be trivially parallelized and be run on multiple cores)
- the third collects the results generated with the second script
- the fourth script allows to compute the RMSE and type I error for each combination of power parameter and sample size
