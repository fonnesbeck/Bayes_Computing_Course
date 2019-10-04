# QuantumBlack Bayes Course

Material for course on Bayesian Computation


## Course Outline

### Monday, October 21
1. Hierarchcial Models (Chris)
    - motivation and case studies
    - partial pooling
    - building hierarchical models
    - parameterizations
    - model checking
2. Markov chain Monte Carlo (Colin)
    - MCMC basics
    - variational inference
    - diagnostics
### Tuesday, October 22
3. The Bayesian Workflow (Colin)
    - prior predictive checks
    - posterior predictive checks
    - model comparison
    - using the model 
4. Bayesian Time Series Models (Chris)
    - modeling repeated measurements
    - structural time series models
    - hierarchical time series models
    - censored data and survival models
    - model checking
### Wednesday, October 23
5. Bayesian Non-parametric Models (Chris)
    - kernel-based models
    - modeling with Gaussian distributions
    - Gaussian processes
    - covariance functions
    - Bayesian optimization
6. Advanced Topics and Software Overview (Colin)
    - Stan
    - PyMC3
    - pyro
    - TensorFlow Probability
    - using GPUs, TPUs

## Setup

This tutorial assumes that you have [Anaconda](https://www.anaconda.com/distribution/#download-section) (Python 3.6 or greater) setup and installed on your system. If you do not, please download and install Anaconda on your system before proceding with the setup.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/fonnesbeck/QB_Bayes_Course.git
    
otherwise you can [download a zip file](https://github.com/fonnesbeck/QB_Bayes_Course/archive/master.zip) of its contents, and unzip it on your computer.
***
The repository for this tutorial contains a file called `environment.yml` that includes a list of all the packages used for the tutorial. If you run:

    conda env create
    
from the main tutorial directory, it will create the environment for you and install all of the packages listed. This environment can be enabled using:

    conda activate bayes_course
    
Then, you can start **JupyterLab** to access the materials:

    jupyter lab

## Pre-course Work

In advance of the course, we would like attendees to complete a short homework notebook that will ensure everyone has the requisite baseline knowledge. You can find this Jupyter notebook in the `/notebooks` subdirectory. There is no need to hand this in to anyone, but please reach out if you have difficulty with any of the problems.
