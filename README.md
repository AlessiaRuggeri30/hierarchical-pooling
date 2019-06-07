# Hierarchical Pooling
## Geometric Deep Learning, course project - USI, 2019
*Alessia Ruggeri*

This project was implemented as a university project for the course of *Geometric Deep Learning* at Università della Svizzera Italiana.

Implemenation of the paper *Towards Sparse Hierarchical Graph Classifier* tested on Enzymes and Proteins datasets using Python 3.6 and Tensorflow 2.0.

The implementation can be found in the `core` folder, which contains the following files and folders:
- `data`: it is a folder that contains the two datasets (Enzymes and Proteins) used to test my model.
- `load_data.py`: it is a file I took from the diffpool repository in order to help me deal with the datasets import. The original can be found at: https://github.com/RexYing/diffpool/blob/master/load_data.py
- `Hierarchical pooling.ipynb`: it contains the whole implementation of the paper's model that I realized. Except for the `load_data.py` file, all the functions, the layers classes, the models classes and the training and testing sections can be found there. The file is well structured and it contains some comments to facilitate the readability of the code.

Read the `Project Report.pdf` file for an in-depht description of the project, the model and the results obtained.

Take a look at the `Project Presentation.pdf` file for a higher-level presentation of the project I made in class.

Link to the official paper *Towards Sparse Hierarchical Graph Classifier*:
https://arxiv.org/abs/1811.01287
