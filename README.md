# Testing EspNet

ESPNet can be described as an "Efficient Spatial Pyramid of Dilated Convolutions for Semantic Segmentation". 

I have trained the model in Anaconda using few sample images which I took in dublin. The test results and described below.

## Simple Steps to Install the required libraries and  Execute the Algorithm in Anaconda.

### Install pytorch Libraries

```bash
conda install pytorch-cpu torchvision-cpu -c pytorch
```
check the pytorch getstarted guide https://pytorch.org/get-started/locally/ for exact command.

Original Image:

<img src="images/IMG_0399.JPG">

c_data Output :
<img src="images/c_data_IMG_0400.png">

Overlay Output :
<img src="images/Overlay_Data_IMG_0400.jpg">
