# 1Shot-MaxPol
A MATLAB Package for Natural Image Deconvolution

----------------------------------------------------------------
### General purpose
You can use this source code to deconvolve naturally blurred images

### Demo Example
![RGB_Hyperspectral_raw_image_23](https://user-images.githubusercontent.com/7947948/61488237-b685ca80-a975-11e9-8ad5-1c3e7248b625.png) ![RGB_Hyperspectral_deblurred_image_23_maxpol](https://user-images.githubusercontent.com/7947948/61488248-bede0580-a975-11e9-8a0f-4926a2d490e4.png)

----------------------------------------------------------------
### Requirements
- MATLAB R2015b (minimum)
- MaxPol package should be installed (download from https://github.com/mahdihosseini/MaxPol)

----------------------------------------------------------------
### MATLAB Codes

Demo function:  
-	demo_image_deblurring.m

Utility functions:  
-	maxpol_downsample.m
-	spectrum_calculation_circular.m
-	blur_kernel_estimation.m
-	generalized_Gaussian_for_fitting.m
-	specrum_fit.m
-	deblurring_kernel_estimation.m
-	OneShotMaxPol.m

----------------------------------------------------------------  
### Published Paper
Paper title: [Convolutional Deblurring for Natural Imaging]  
Paper Download: [https://arxiv.org/abs/1810.10725]  (IEEE link commin soon!)

----------------------------------------------------------------
### Author  
Mahdi S. Hosseini  
Email: mahdi.hosseini@mail.utoronto.ca  
http://www.dsp.utoronto.ca/~mhosseini/  

----------------------------------------------------------------
### Citation  
@article{hosseini2018convolutional,  
  title={Convolutional Deblurring for Natural Imaging},  
  author={Hosseini, Mahdi S and Plataniotis, Konstantinos N},  
  journal={accepted for publication in IEEE Transaction Image Processing},  
  year={2019}  
}
