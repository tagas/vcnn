# Retrospective Uncertainties for Deep Models using Vine Copulas

This repository contains an implementation of the VCNN, as descibed in ["Paper submission 1289 - Retrospective Uncertainties for Deep Models using Vine Copulas"]

<center>
    <img src="intro.png?raw=true" width="750">
</center>
Visual abstract: We propose a plug in vine-copula
module that can complement any neural network with a pre-
diction interval, any time after the model has been trained,
without requiring any modifications to it. Additionally, our
prediction intervals capture both - aleatoric and epistemic
uncertainty.

## User guide


### Dependencies
Download or clone this repository. VCNN relys on both R and Python packages. Hence, base R and the connecting package "rpy2" should be installed. Then within R, the following libraries are required: rvinecopulib, eecop, and stats.


### Example
An example demo can be found in the notebook ``` demo.ipynb```.
