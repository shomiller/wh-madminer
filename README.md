# Analyzing WH Production with MadMiner

**By Johann Brehmer, Sally Dawson, Samuel Homiller, Felix Kling, and Tilman Plehn**

## Introduction

This repository contains the notebooks used for generating and analyzing the simulation data for the paper ["Benchmarking simplified template cross sections in WH production"](https://arxiv.org/abs/1908.06980) using the inference-toolkit [MadMiner](https://github.com/diana-hep/madminer).

The analysis proceeds in several steps:
* Setup of the morphing basis (choosing the parameters which will be varied in the model file)
* Generation of the signal and background samples
* Analyzing/pre-processing of the LHE files (this is where observables are chosen and computed)
* Setup and training of the SALLY estimators
* Computation of the Fisher Information using the SALLY estimators or in histograms.

Additional files for estimating limits on the squared terms, or using the HARRY setup, require a different branch of MadMiner. Notebooks for computing the limits in this branch will be added at a later date, or are available upon request. 
