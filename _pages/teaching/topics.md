---
layout: default 
title: Thesis topics (Bc, Mgr)
permalink: /teaching/topics/
---

I offer topics in the field of Neural architecture search, mostly in performance prediction (but reach out if
 you have a specific topic in NAS or AutoML in mind). Depending on the results, the thesis could lead to a scientific
publication.

### 1. Joint performance prediction
Existing performance prediction works in NAS dealt with cell-based search spaces only - i.e., predicting
the validation accuracy of a network based on its graph structure. However, in practice, we often vary
other hyperparameters of the network, such as the number of filters, kernel size, etc., as well as parameters of
the training (learning rate, batch size, SGD/Adam, etc.). Joint search spaces optimize both the architecture and
hyperparameters of a network. The goal of this thesis is to propose novel methods for joint performance prediction
and compare them with existing predictors.

### 2. Graph neural networks for performance prediction
Graph neural networks were successfully applied in performance prediction in NAS. However, a larger study on what
graph neural architectures are the most suitable for performance prediction is missing. Similarly, different predictor
training schemes could be used (e.g. binary relation predictor vs regressor). The goal of this thesis is to compare
existing graph neural architectures and training schemes for performance prediction. It would be great to explore more
recent GNNs that were not used in NAS performance prediction yet.