# IFPEN-residual-oil-saturation-prediction

## Short description
Use rock porous microstructure given as a 3D image to predict the amount of residual oil and the size of the oil clusters in this microstructure.

Video of the challenge's presentation at Collège de France is available at: https://www.college-de-france.fr/site/stephane-mallat/Challenge-2017-2018-Prediction-de-la-saturation-d-huile-residuelle-par-IFPEN.htm

## Challenge context
Assessing remaining oil and gas reserves and predicting how much can be recovered from a given reservoir is a critical issue for planning energy policies in the near future. The recoverable oil quantity in a reservoir strongly depends on the microstructure of the underlying rock type that composes the porous media. Experimental techniques allow to accurately observe the rock microstructure as 3-dimensionnal images and identify pores, oil and solid matrix in a typical rock. 

IFPEN possesses experimental data that show rock sample microstructures before any contact with fluids, and after oil immersion followed by a water flush, allowing to measure the amount of residual oil trapped in the rock sample.Unfortunately, physical models are not able to predict how much residual oil will remain in each sample, nor where these oil clusters will be located.

## Challenge goals
The objective of the challenge is then to build a model by which, given an initial rock microstructure, one can predict the amount of residual oil and the size of the oil clusters.

## Data description
The participants are given a training set of 400 experiments consisting of two separate files where 
input files are 3D images of a porous rock and where output ones are the corresponding 3D images of the same rock matrix but with residual oil in pores.


* Training Data

** Input & Output Image files

Each training input (resp. output) file is listed as input_[id].raw (resp. output_[id].raw) where id is the experiment id number (with 0
