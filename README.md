# pyEDA
This is the initial release for pyEDA v.1.0.
<br />This package includes all you need for Electrodermal Activity analysis also known as GSR. It contains preprocessing of the EDA signal and its feature extraction.

# Data collection
All the plots and the data collected for this package are comming from Shimmer GSR+ wearable sensor. If you are using other sensors to collect EDA signal, you may need to use your own openShimmerFile.py based on your file. Otherwise, you can use openShimmerFile.py with minor changes. 

# Installation

# Documentation
Here you can find the link to different notebooks about all the aspects of analysis of the GSR signal. These documentations include information about preprocessing and feature extraction of EDA signal.
<br />
<br />
These show how to handle various analysis tasks with pyEDA, from noisy data collected from Shimmer GSR+.
<br />
<br />
Here you can find the list of notebooks starting from preprocessing of EDA signal to extracting its features.
* GSR windowing, a notebook explaining about windowing process of GSR signal using HeartPy package for windowing.
* GSR preprocessing, a notebook explaining preprocessing part of GSR.
  * Downsampling
  * Moving Window Averaging
  * Normalization
  * Extracting tonic and phasic components of signal using cvxPDA.py.
  * Butterworth Low pass filter
* GSR feature extraction, a notebook explaining feature extraction of GSR.
  * Number of peaks
  * Maximum value of GSR
  * Mean value of GSR