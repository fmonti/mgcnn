# Multi-Graph Convolutional Neural Networks
The code contained in this repository represents a TensorFlow implementation of the Recurrent Muli-Graph Convolutional Neural Network depicted in:

Geometric Matrix Completion with Recurrent Multi-Graph Neural Networks (in Proc. NIPS, 2017)<br>
Federico Monti, Michael M. Bronstein, Xavier Bresson

https://arxiv.org/abs/1704.06803

## Repository Structure 

The repository is organized in two main folders: Notebooks and Data. Notebooks contains the python scripts we exploited for realizing the experiments depicted in the paper. Data, the datasets we used.

Every single folder is divided in 5 different subfolders, representing the 5 different datasets we used in our experiments: Movielens 100K, Douban, Flixster, Yahoo Music and our Synthetic Dataset. 

## When shall I use this method?

MGCNN is a Multi-Graph CNN able to operator on signals defined on multiple graphs. In the paper we exploited this solution for solving the recommendation problem. However, the architecture is general and can be used for any multi-graph dimensional signal.
