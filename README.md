# Astrophysics Undergraduate Thesis

A repository containing jupyter notebook interface of a Convolution Neural Network Model to identify stellar wind bubbles in galaxies. 

This model is trained on galaxy NGC 0628 as it is the only galaxy who has been subjected to a stellar-wind bubble analysis ( J. Watkins et al 2023 ApJL )

## Basic CNN model

To get a taste of how convolutional neural network works, directory `CNN training` provides a good overview of the setup.

```
1. jwst-bubbles-v0p1.reg contains information regarding the bubbles
2. ngc0628_miri_f770w_anchored.fits is a fits file which contains the image of the galaxy NCG 0628 and can be easily plotted using astropy library in python.
```

## U-NET architecture

