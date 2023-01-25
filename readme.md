# Dataset
I use CT-ORG as the dataset https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=61080890#6108089070508a07758449c19ca1c9e687ae4d05 

## Resample 

resample and standardize the dataset images to have a maximal resolution of 256x256 pixels and to have a maximum of 300 volumetric slices

# DONE

## Preprocessing methods

- Histogram Equalization
- Resizing
- Normalization

# TODO

## Preprocessing methods
- Data Augmentation (Elastic transformation, Rotation, Flip)

## Post processing methods 
- Morphological operations/Hole filling
- Smoothing
- Thresholding

## Evaluate model

- Confusion matrix
