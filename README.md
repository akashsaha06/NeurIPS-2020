# Code for Learning with Operator-valued Kernels in Reproducing Kernel Krein Spaces
This GitHub repository contains codes used for NeurIPS 2020 paper 'Learning with Operator-valued Kernels in Reproducing Kernel Krein Spaces.'

## Paper
[Learning with Operator-valued Kernels in Reproducing Kernel Krein Spaces (NeurIPS 2020)](https://proceedings.neurips.cc/paper/2020/hash/9f319422ca17b1082ea49820353f14ab-Abstract.html)

### Abstract
   Operator-valued kernels have shown promise in supervised learning problems with functional inputs and functional outputs. The crucial (and possibly restrictive) assumption of positive definiteness of operator-valued kernels has been instrumentalin developing efficient algorithms. In this work, we consider operator-valued
kernels which might not be necessarily positive definite. To tackle the indefiniteness of operator-valued kernels, we harness the machinery of Reproducing Kernel Krein
Spaces (RKKS) of function-valued functions. A representer theorem is illustrated which yields a suitable loss stabilization problem for supervised learning with
function-valued inputs and outputs. Analysis of generalization properties of the proposed framework is given. An iterative Operator based Minimum Residual
(OpMINRES) algorithm is proposed for solving the loss stabilization problem. Experiments with indefinite operator-valued kernels on synthetic and real data sets
demonstrate the utility of the proposed approach.

### Citation
To cite this work, you can use the following bibtex entry:
 ```bib
@inproceedings{NEURIPS2020_9f319422,
 author = {Saha, Akash and Palaniappan, Balamurugan},
 booktitle = {Advances in Neural Information Processing Systems},
 editor = {H. Larochelle and M. Ranzato and R. Hadsell and M.F. Balcan and H. Lin},
 pages = {13856--13866},
 publisher = {Curran Associates, Inc.},
 title = {Learning with Operator-valued Kernels in Reproducing Kernel Krein Spaces},
 url = {https://proceedings.neurips.cc/paper/2020/file/9f319422ca17b1082ea49820353f14ab-Paper.pdf},
 volume = {33},
 year = {2020}
}

```

## About Code

### Dependencies:
    Python version: 3.7
    Packages: numpy, scipy, matplotlib, and time

### File Descriptions:
OpMINRES.ipynb contains the implementation of OpMINRES algorithm for a synthetic dataset using generalized operator-valued kernel. A particular choice of generalized operator-valued kernel has been considered in this implementation. Various other choices based on the kernels considered can be found in the paper.

### Contact for any query:
    akashsaha@iitb.ac.in
