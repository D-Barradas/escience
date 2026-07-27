---
title: Tutorial 4
nav_order: 7
---

# Tutorial 4

## Deep Learning Workflows with Skorch and RAPIDS

This notebook focuses on model development workflows that combine Skorch with GPU-enabled tooling, giving attendees a reusable pattern for deep learning experimentation in notebook form.

<a href="https://colab.research.google.com/github/D-Barradas/Accelerated-Data-Science-with-RAPIDS/blob/main/part4/4-01_HPO_Ray_RAPIDS_MNIST.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

##  Distributed Hyperparameter Optimization with Ray Tune and RAPIDS

#### What is RayTune?

&emsp; &emsp; &emsp; [RayTune](https://ray.readthedocs.io/en/latest/index.html) is a scalable Hyperparameter optimization library. It allows distributed HPO, provides various [search algorithms](https://ray.readthedocs.io/en/latest/tune-searchalg.html) to allow different optimization techniques to be explored with ease. The library also provides [scheduling algorithms](https://ray.readthedocs.io/en/latest/tune-schedulers.html) that allows a smarter way to schedule the different parameter sweep instead of the basic First In-First Out method which is followed by other libraries (Scikit-Learn, Dask-ml) that support HPO. The different scheduling algorithms can make the HPO process resource efficient and help arrive at the best parameters much faster.

<a href="https://colab.research.google.com/github/D-Barradas/Accelerated-Data-Science-with-RAPIDS/blob/main/part4/4-02_HPO_Ray_RAPIDS_MNIST.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

## What you will do

- open a ready-to-run Colab notebook
- work through a GPU-based deep learning training workflow
- experiment with tuning and evaluation in an interactive environment
- adapt the notebook for follow-up research projects

## Notebook source

- [Notebook in GitHub repository](https://github.com/D-Barradas/Accelerated-Data-Science-with-RAPIDS/blob/main/part4/4-02_HPO_Ray_RAPIDS_MNIST.ipynb)
- [Repository root](https://github.com/D-Barradas/Accelerated-Data-Science-with-RAPIDS)
