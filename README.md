# Astrophysics Undergraduate Thesis

A repository containing jupyter notebook interface of a Convolution Neural Network Model to identify stellar wind bubbles in galaxies. 

This model is trained on galaxy NGC 0628 as it is the only galaxy who has been subjected to a stellar-wind bubble analysis ( J. Watkins et al 2023 ApJL )

## Basic CNN model

To get a taste of how convolutional neural network works, directory `CNN training` provides a good overview of the setup.

1. jwst-bubbles-v0p1.reg contains information regarding the bubbles
2. ngc0628_miri_f770w_anchored.fits is a fits file which contains the image of the galaxy NCG 0628 and can be easily plotted using astropy library in python.


## U-NET architecture

Contains 4 directories:
1. 0-1 dir neglects overlapping bubbles and treat them as a part of a single bubble (main emphasis of the study)
2. '>'1 takes into account overlapping region (needed a completely new research study as U-NET model based on 0-1 technique didn't perform as well)
3. NGC0628 dir contains the ground truths to train the model
4. dataset dir provides an example of the training set
