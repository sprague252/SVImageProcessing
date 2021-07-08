# ECU Summer Ventures Jupyter Notebooks for Image Processing in Python

This repository contains Jupyter notebooks that use *Python* to do basic image processing including importing RAW and other image files, separating color channels, and computing spatial Fourier transfroms and power spectra of color data.

## Run on your computer

Run on your computer (with python and Jupyter already installed). First clone this git repository from GitHub with the following command.
```
git clone https://github.com/sprague252/SVImageProcessing.git
```
You must have `python3`, `numpy`, `matplotlib`, `rawpy` (install this with `pip`), and `pillow` installed to use this. 

Once you have everything configured, start Jupyter Notebook or Jupyter Lab and open the notebook `Image Processing.ipynb`. 

## Run on CoCalc

The files should be already installed in your [CoCalc](https://cocalc.com) Summer Ventures project. (Look in Handouts.) If not, you can open a Linux terminal and run the `git` command in the previous section to copy them. Once you have the files, open `Image Processing.ipynb` in CoCalc. Be sure to set the kernel to `Python 3 (system-wide)` because that contains all of the modules you will need.

## Run on Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sprague252/SVImageProcessing/master) No login necessary. Wait for binder to build the virtual server, and then open the notebook `Image Processing.ipynb`.