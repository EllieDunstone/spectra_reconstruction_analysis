# Spectra reconstruction analysis

NOTE: No promises on which parts of this are currently working, this is very much work-in-progress right now!

## Introduction

This repo contains code for analysing and exploring the quality of the spectrum reconstructions generated during signature extraction or fitting using sigfit, which can be installed from <https://github.com/kgori/sigfit>. Reconstructions of your samples under the 'model' you have calculated can be produced for all three modalities implemented in sigfit: reference signature fitting; de novo signature extraction; and combined fitting and extraction (FitExt). For further explanation, see the vignettes on the sigfit github, or my own 'sigfit_signature_analysis.Rmd' script that implements the sigfit package.

Sigfit allows us to examine how effectively the estimated signatures and/or exposures can reconstruct the original mutational catalogues by producing spectrum reconstruction plots with the 'plot_reconstruction' function. The underlying data can be accessed using the 'get_reconstructions' function, which provides the input data for this script. Some of the content of this script is adapted from the 'plot_reconstruction' function written by the authors of sigfit.


## Scripts

The spectra_reconstruction_analysis.Rmd script can be used to perform this analysis interactively on your own data, or as a vignette to demonstrate how the analysis works.

?Add description of stand-alone functions if i add script for these
?Add description of example data once added


## Dependencies

The scripts load the following libraries, which will need to be installed prior to running:

* tidyverse
* patchwork
* sigfit (see <https://github.com/kgori/sigfit>)

## Usage

See the spectra_reconstruction_analysis.Rmd script or its .html output for further documentation of usage.


## Acknowledgments

Parts of this code are adapted from the original sigfit package written by Adrian Baez-Ortega and Kevin Gori <https://github.com/kgori/sigfit>. These scripts were written for the downstream analysis of data generated using this package.
