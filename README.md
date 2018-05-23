# ugtm v1.1.2: Generative Topographic Mapping with Python.

Link to the package documentation: http://ugtm.readthedocs.io/en/latest/

GTM (Generative Topographic Mapping) is a dimensionality reduction algorithm (as t-SNE, LLE, etc) created by Bishop et al. (https://www.microsoft.com/en-us/research/wp-content/uploads/1998/01/bishop-gtm-ncomp-98.pdf) and a probabilistic counterpart of Kohonen maps.

ugtm is a python package implementing GTM and GTM prediction algorithms. ugtm contains the core functions and runGTM.py (in bin directory) is an easy-to-use program. The kernel version of the algorithm (kGTM) is also implemented. You can also generate regression or classification maps, or evaluate the predictive accuracy (classification) or RMSE/R2 (regression) in repeated cross-validation experiments.

## Install ugtm

pip install ugtm

## Documentation

[Readthedocs](http://ugtm.readthedocs.io/en/latest/)


## Prerequisites

Python 2.7 or + (tested on Python 3.4.6 and Python 2.7.14)

and following packages:
- sklearn>=0.0
- numpy>=1.13.1 
- matplotlib>=2.0.2
- scipy>=0.19.1
- mpld3>=0.3


## Author

Héléna A. Gaspar, hagax8@gmail.com, https://github.com/hagax8


