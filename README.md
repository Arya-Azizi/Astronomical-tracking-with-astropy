This Python script is designed for the analysis of astronomical data from a FITS (Flexible Image Transport System) file using various libraries, including NumPy, SEP (Source Extractor in Python), Astropy, and Matplotlib. The script performs the following tasks:

## Importing Required Packages:

- numpy is imported for numerical data manipulation.
- sep (Source Extractor in Python) is used for source detection and background estimation.
- astropy.io.fits is used to work with FITS files.
- matplotlib.pyplot is used for data visualization.

## Defining the File Path:
- The script defines the path to the FITS file to be analyzed on your Mac. Please make sure to update this path to match the location of your FITS file.

## Reading FITS Data:
- The script reads the data from the FITS file into a 2D NumPy array.

## Plotting and Saving the Image:
- The data is visualized using Matplotlib and saved as an image file.

## Background Estimation:
- The script estimates the background in the image using the SEP library.
## Subtracting Background:
- The estimated background is subtracted from the original data.
## Object Detection:
- Objects are detected in the image using a specified detection threshold.
- Ellipses are plotted around detected objects.

## Circular Aperture Photometry:
- Circular aperture photometry is performed on the detected objects to measure their flux.

## Plotting a Histogram:
- A histogram of object fluxes is created and saved as an image.
