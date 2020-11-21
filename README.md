# Projet_long_analaysisProteinTrajectories

Using dimensionality reduction to analyze protein trajectories. 

project statement :
=> The exploration of conformational properties from molecular dynamics simulations often requires appropriate processing of data to distinguish major characteristic movements 
from those related to the stochastic character of the dynamics. 
Based on the publication (Front. Mol. Biosci., 19 June 2019 | https://doi.org/10.3389/fmolb.2019.00046, you will develop either in C ++ or in python, the routines capable of reading data 
from trajectories and process them using the different approaches proposed in the publication (t-SNE, PCA, isomap, Laplacian Eigenmaps and sketch-map). 
The methods will be compared on a few examples provided. 

package needed :
=> mdtraj
conda environment : 
1) conda create --name mdtenv
2) conda activate mdtenv
3) conda install -c conda-forge mdtraj

Installation of juppyter lab in the env:
4)conda install -c conda-forge jupyterlab
5) run with : jupyter-lab or jupyter lab

Installation of sklearn
6)conda install -c intel scikit-learn
