# Bayesian Computing Course

Material for course on Bayesian Computation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fonnesbeck/Bayes_Computing_Course/master)

## Setup

This tutorial assumes that you have [Anaconda](https://www.anaconda.com/distribution/#download-section) (Python 3.6 or 3.7) setup and installed on your system. If you do not, please download and install Anaconda on your system before proceding with the setup.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/fonnesbeck/Bayes_Computing_Course.git

otherwise you can [download a zip file](https://github.com/fonnesbeck/Bayes_Computing_Course/archive/master.zip) of its contents, and unzip it on your computer.
***
The repository for this tutorial contains a file called `environment.yml` that includes a list of all the packages used for the tutorial. If you run:

    conda env create

from the main tutorial directory, it will create the environment for you and install all of the packages listed. This environment can be enabled using:

    conda activate bayes_course

Then, you can start **JupyterLab** to access the materials:

    jupyter lab

The binder link above should also provide a working environment.

## Pre-course Work

In advance of the course, we would like attendees to complete a short homework notebook that will ensure everyone has the requisite baseline knowledge. You can find this Jupyter notebook in the `/notebooks` subdirectory (under `Section0-Pre_Work.ipynb`). There is no need to hand this in to anyone, but please reach out if you have difficulty with any of the problems (or with setting up your computing environment) by creating an [issue](https://github.com/fonnesbeck/Bayes_Computing_Course/issues) in this repository, or by emailing.

## Course Outline

This is subject to change. We will seek input at the end of each day and try to accommodate where there is interest.

Roughly, the first half of the course jumps right in with applied examples, then steps back to cover some of the theory behind Bayesian methods before going carefully through another applied case study. The second half of the course is a variety of more advanced topics, currently covering time series, Bayesian non-parametrics, and the landscape of open source software available for doing Bayesian work.

### Wednesday, January 8

1. **Hierarchcial Models** (Chris) 9:00am - 12:00pm
    - Motivation and case studies
    - Partial pooling
    - Building hierarchical models
    - Parameterizations
    - Model checking
2. **Markov chain Monte Carlo** (Colin) 1:00pm - 4:00pm
    - Probability density functions, inverse CDF sampling
    - Rejection sampling
    - MCMC basics
    - Metropolis-Hastings samplers
    - Gibbs samplers

### Thursday, January 9

3. **Modern Markov chain Monte Carlo** (Colin) 9:00am - 12:00pm
    - Hamiltonian Monte Carlo
    - Introduction to diagnostics
4. **The Bayesian Workflow** (Colin)
    - Prior predictive checks
    - Iterating models
    - Posterior predictive checks
    - Using the model
5. **Bayesian Time Series Models** (Chris) 1:00pm - 4:00pm
    - Modeling repeated measurements
    - Structural time series models
    - Hierarchical time series models
    - Censored data and survival models
    - Model checking

### Friday, January 10

6. **Bayesian Non-parametric Models** (Chris) 9:00am - 12:00pm
    - Kernel-based models
    - Modeling with Gaussian distributions
    - Gaussian processes
    - Covariance functions
    - Bayesian optimization
7. **Advanced Topics, software overview, wrap-up** (Colin) 1:00pm - 4:00pm
    - Stan
    - PyMC3
    - pyro
    - TensorFlow Probability
    - using GPUs, TPUs
