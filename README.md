# CASML24Workshop
Material for the preconference workshop on Scientific Machine Learning at the International Conference on Applied AI and Scientific Machine Learning (CASML) 2024

## Basics of Tensorflow and Numpy

In this section, we will look at the basics required to get started with Tensorflow and Numpy. These will be the building blocks for developing Physics-Informed Neural Networks (PINNs) and Variational Physics-Informed Neural Networks (vPINNs).

Repository Link: [Click Here](https://github.com/thivinanandh/Teaching-Python)

Navigate to `Python-Libraries` ( [link](https://github.com/thivinanandh/Teaching-Python/tree/main/Python-Libraries) )folder and open the Numpy and Tensorflow notebooks. Each of the notebook has "open in colab" button which will open the notebook in Google Colab. 

Easy Access links

- [Numpy](https://github.com/thivinanandh/Teaching-Python/blob/main/Python-Libraries/Numpy.ipynb)
- [Tensorflow](https://github.com/thivinanandh/Teaching-Python/blob/main/Python-Libraries/Tensorflow.ipynb)

## PINNs_workshop

This folder contains resources for the **Physics-Informed Neural Networks (PINNs)** workshop. It includes two Jupyter notebooks that demonstrate different aspects of solving forward and inverse problems using PINNs.

- [Forward Problem Notebook](https://colab.research.google.com/github/airex-lab/CASML24Workshop/blob/main/PINNs_workshop/forward_problem.ipynb)  
  This notebook demonstrates the solution of a forward problem using PINNs, focusing on the application of neural networks to solve partial differential equations (PDEs).
  
- [Inverse Problem Notebook](https://colab.research.google.com/github/airex-lab/CASML24Workshop/blob/main/PINNs_workshop/inverse_problem.ipynb)  
  This notebook explores the solution of an inverse problem using PINNs, where the goal is to infer unknown parameters or functions from data.

## hp-VPINNs

This folder contains resources for the hp-Variational Physics-Informed Neural Networks (hp-VPINNs)

- Visit the FastVPINNs repository [here](https://github.com/cmgcds/fastvpinns)
- `Fork` the repository to your GitHub account by clicking on the `Fork` button on the top right corner of the repository page.
- Navigate to the forked repository in your GitHub account and click on the `Code` button to copy the repository URL.
- Now, open your terminal and clone the repository to your local machine using the following command:
  ```bash
  git clone https://github.com/cmgcds/fastvpinns.git
  ```
  - Now, for offline use, navigate to the examples folder -> Notebooks -> `custom_training_poisson.ipynb` and open the notebook in Jupyter Notebook or Jupyter Lab.
  - For online use, click on the `Open in Colab` button to open the notebook in Google Colab.

## Navier Stokes 2D Workshop

- [Falkner-Skan Notebook](https://colab.research.google.com/github/airex-lab/CASML24Workshop/blob/main/NSE_2D_workshop/PINNs_FS.ipynb)  
  This notebook demonstrates the solution of a Falkner-Skan Boundary layer using PINNs.

## References

1. Raissi, M., Perdikaris, P., & Karniadakis, G. E. (2019). Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations. *Journal of Computational Physics*, 378, 686-707. [DOI](https://www.sciencedirect.com/science/article/pii/S0021999118307125)

2. Anandh, T., Ghose, D., & Ganesan, S. (2024). FastVPINNs: An efficient tensor-based Python library for solving partial differential equations using hp-Variational Physics Informed Neural Networks. *Journal of Open Source Software*, 9(99), 6764. [DOI](https://joss.theoj.org/papers/10.21105/joss.06764.pdf)

