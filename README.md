# Predicting the age of abalone
This is a small project utilizing linear bayesian model based on PyMC3 to predict the age of abalone.

## What is PyMC3
There is a fully developed package called **PyMC3** that concerns the probabilistic programming for bayesian modeling and probabilistic machine learning with *Theano*.

**PyMC3** is powered by NumFOCUS, see PyMC3 documentation at http://docs.pymc.io/index.html

## Age of abalone, a physical measurement
> The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of **rings** through a microscope -- a boring and time-consuming task.

Thus, a more convenient way to know the age of abalone is to estimate it using other physical measurement such as weight, length, diameter etc. 

**In this small project, I use the data of abalone which includes their different physical measurement and rings, so as I can use a linear bayesian model to investigate the relation between the age (i.e rings) and a set of other covariates.** 

The data is from Kaggle(a platform for predictive modelling and analytics competitions), you can download it at https://www.kaggle.com/rodolfomendes/abalone-dataset/version/3#
