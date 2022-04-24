# Image-Quality-Assessment
Given an RGB image, predict a floating number (either in range 0-1, 1-10 or 1-100) which describes the quality of an image.
# IMA
Image quality is a notion that highly depends on observers. Generally, it is linked to the conditions in which it is viewed; therefore, it is a highly subjective topic. Image quality assessment aims to quantitatively represent the human perception of quality.

Generally, Image Quality Analysis(IQA) is divided broadly into two types,

1). Reference Based Evaluation

2). No-Reference Evaluation.

The main difference is that reference-based methods depend on a high-quality image as a source to evaluate the difference between images.
# Blind/referenceless image spatial quality evaluator (BRISQUE)
For this project, I've used a model known as "BRISQUE" which basically comes under No-reference Image Quality Assessment.

BRISQUE is a model that only uses the image pixels to calculate features. It relies on spatial Natural Scene Statistics (NSS) model of locally normalized luminance coefficients in the spatial domain, as well as the model for pairwise products of these coefficients.

It is better than the other approaches as other methods are based on image transformation to other spaces like wavelet or DCT and brisque only uses the image pixels. Another advantage of using BRISQUE is that the BRISQUE score correlates well with human perception of quality.
