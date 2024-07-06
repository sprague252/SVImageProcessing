# ECU Summer Ventures Jupyter Notebooks for Image Processing in Python

This repository contains Jupyter notebooks that use *Python* to do basic image processing including importing RAW and other image files, separating color channels, and computing spatial Fourier transfroms and power spectra of color data.

## Run on your computer

Run on your computer (with python and Jupyter already installed). First clone this git repository from GitHub with the following command.
```
git clone https://github.com/sprague252/SVImageProcessing.git
```
You must have `python3`, `numpy`, `matplotlib`, `rawpy` (install this with `pip`), and `pillow` installed to use this. 

Once you have everything configured, start Jupyter Notebook or Jupyter Lab and open the notebook `Image Processing.ipynb`. 

## Run on Google Colab

<a target="_blank" href="https://colab.research.google.com/github/sprague252/SVImageProcessing/blob/master/ImageProcessingColabSetUp.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

The easiest way to run these notebooks is to use [Google Colab](https://colab.research.google.com/), which will use computers in the Google cloud to run the Python code. In order to do this, you must have a Google account with sufficient space on your Google Drive. 

In order to run these files on Colab, open the notebook `ImageProcessingColabSetUp.ipynb` and run the commands in Colab. You can do open the notebook with the following link.

[Open ImageProcessingColabSetUp.ipynb on Google Colab.](https://colab.research.google.com/github/sprague252/SVImageProcessing/blob/master/ImageProcessingColabSetUp.ipynb)

## Run on Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sprague252/SVImageProcessing/master) No login necessary. Wait for binder to build the virtual server, and then open the notebook `Image Processing.ipynb`.