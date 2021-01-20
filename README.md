# R244-Open-Source-Mini-Project
Public repo for the open-source mini-project for the R244 module. 

This repository contains: 
* `ModelCompression.ipynb` - containing the implementation of the compression techniques (defined in `apply_compression`) as well as the optimisation experiments with Ax. 
* `AnalysingResults.ipynb` - contains code for plotting graphs, processing and analysing the data obtained from the experiments. 
* `/results` - contains the results from the experiments. Random and grid search are saved as `pickle` files while Ax experiments are saved via their Ax clients (in `.JSON` files). 
* `/graphs` - contains the `.png` and `.svg` versions for the PyPlot graphs used in the report. 
* `/baseline_models` - contains the saved baseline model used for evaluating the performance of the optimisation strategies. 
* `data` - includes the MNIST dataset. 