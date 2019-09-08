---
layout: page
weight: 5
title: Labs
---

The labs for the Gaussian Process Summer School can be downloaded here. All of the lab sheets are written in Python 3 given in Jupyter notebook format.

Each lab sheet will be made available on the day of the lab, and answers for each will be made shortly after. There are also some extra work sheets, for you to explore in your own time, which give details of other uses of Gaussian processes not covered in the summer school. Answers for extra labs will be made available after the summer school.


Details of how to set up your Python environment and on the installation of the necessary libraries are available on the [Getting Started](../getting_started) page. Ensure you have completed the setup before starting the labs. We recommend that you use Binder during the lab sessions. To view and run the full list of labs, click here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gpschool/labs/2019?filepath=2019%2F). Alternatively, you can use the corresponding links for each lab.

### Lab 1: Gaussian Process Regression
This lab is designed to introduce Gaussian processes in a practical way, illustrating the concepts introduced in the first two lectures. The key aspects of Gaussian process regression are covered: the covariance function (aka kernels); sampling a Gaussian process; and the regression model. The notebook will introduce the open source Python library GPy which handles the kernels, regression and optimisation of hyperparameter, allowing us to easily access the results we want.

[![Download](https://img.shields.io/badge/download-lab%201-green)](https://github.com/gpschool/labs/raw/2019/2019/lab_1.ipynb) &nbsp;&nbsp;&nbsp; [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gpschool/labs/2019?filepath=2019%2Flab_1.ipynb) &nbsp;&nbsp;&nbsp; [![Answers](https://img.shields.io/badge/answers-unavailable-red)](#)

Resources: [mauna_loa](https://github.com/gpschool/labs/raw/2019/.resources/mauna_loa)

#### Lab 1 Extra: Uncertainty Propagation
This lab is an extension on the work introduced in Lab 1 of the summer school. It is more advanced, and you should make sure you've completed Lab 1 before attempting. It is designed to demonstrate the advantage of using models when we have only a small number of observations of a latent function.
 
[![Download](https://img.shields.io/badge/download-lab%201%20extra-green)](https://github.com/gpschool/labs/raw/2019/2019/lab_1_extra.ipynb)&nbsp;&nbsp;&nbsp;[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gpschool/labs/2019?filepath=2019%2Flab_1_extra.ipynb)&nbsp;&nbsp;&nbsp;[![Answers](https://img.shields.io/badge/answers-unavailable-red)](#)

### Lab 2: GPs for Non-Gaussian Likelihoods and Big Data
This lab introduces Gaussian process regression for data with non-Gaussian likelihoods, and shows how this can be applied to classification. The concept of sparse methods for Gaussian process regression is introduced for creating a scalable regression model, and this is combined with a large classification problem.

As with Lab 1, the notebook uses GPy for handling the regression model and likelihoods.

You will need to also download the banana.csv dataset for one of the examples in the lab.

[![Download](https://img.shields.io/badge/unavailable-lab%202-red)](https://github.com/gpschool/labs/raw/2019/2019/lab_2.ipynb)&nbsp;&nbsp;&nbsp;[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gpschool/labs/2019?filepath=2019%2Flab_2.ipynb)&nbsp;&nbsp;&nbsp;[![Answers](https://img.shields.io/badge/answers-unavailable-red)](#)

Resources: [olympic_marathon_men](https://github.com/gpschool/labs/raw/2019/.resources/olympic_marathon_men) | [banana.csv](https://github.com/gpschool/labs/raw/2019/.resources/banana.csv) 

<!-- 
#### Lab 2 Extra: Deep Gaussian Processes

[![Download](https://img.shields.io/badge/unavailable-lab%202%20extra-red)](https://github.com/gpschool/labs/raw/2019/2019/lab_2_extra.ipynb)&nbsp;&nbsp;&nbsp;[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gpschool/labs/2019?filepath=2019%2Flab_2_extra.ipynb)&nbsp;&nbsp;&nbsp;[![Answers](https://img.shields.io/badge/answers-unavailable-red)](#)
-->


### Lab 3 : Global Optimisation with Gaussian Processes
This lab introduces the basic concepts of Bayesian optimisation with GPyOpt. The student will have to build and compare different models and aquisition functions to solve several optimisation problems.

[![Download](https://img.shields.io/badge/unavailable-lab%203-red)](https://github.com/gpschool/labs/raw/2019/2019/lab_3.ipynb)&nbsp;&nbsp;&nbsp;[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gpschool/labs/2019?filepath=2019%2Flab_3.ipynb)&nbsp;&nbsp;&nbsp;[![Answers](https://img.shields.io/badge/answers-unavailable-red)](#)


<!-- 
#### Lab 3 Extra: Unsupervised Learning with Gaussian Processes

[![Download](https://img.shields.io/badge/unavailable-lab%203%20extra-red)](https://github.com/gpschool/labs/raw/2019/2019/lab_3_extra.ipynb)&nbsp;&nbsp;&nbsp;[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gpschool/labs/2019?filepath=2019%2Flab_3_extra.ipynb)&nbsp;&nbsp;&nbsp;[![Answers](https://img.shields.io/badge/answers-unavailable-red)](#)
-->

