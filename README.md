# EC601-HW3
This is as a part of Boston University College of Engineering course EC601:Product Design in ECE.


**Exercise 1**:

Mat.data gives a pointer which refers to the original data matrix. In this data matrix, all the pixel values are stored in 1D array. i.e. b1,g1,r1,b2,g2,r2 and so on. Images in OpenCV are stored in the format of BGR and not RGB. So, if we have an image having 512x512 pixels, pixels in first row and first column will have some value like b00, g00 and r00. As per this the pixel in nth row and mth column will have values bnm, gnm and rnm.


**Exercise 2**:
The values of the pixel at (20,25) in the RGB, YCbCr and HSV versions of the image:
    
    1.RGB=[106 122 225]
    2.YCbCr=[151 181 103]
    3.HSV=[4 135 225]

**Exercise 3**:

**Change the kernel sizes for all the filters with all different values for noises and print the results for 3x3, 5x5 and 7x7 kernels. Comment on the results. Which filter seems to work "better" for images with salt-and-pepper noise and gaussian noise?**

An increased Kernel size results in more blurry pictures. Median filter works better for Salt and Pepper Noise while Gaussian filter works better for Gaussian Noise.

**Exercise 4**:

**1. Look at Threshold.cpp and implement the code in Python, and observe the results for different threshold values. Comment on the results.**

The output images have different tones in certain areas depending on the Thresholding used. The adaptive filtering retains most characteristics of the original grayscale image.

**2. What are the disadvantages of binary threshold?**

Binary threshold just gives two values depending on the pixel intensity as compared to threshold. Thus we get an image that just has two pixel values and less characteristics as compared to original.

**3. When is Adaptive Threshold useful?**

Adaptive Threshold is useful in cases where an image has different lighting conditions. Thus it helps us retain maximum details from the original image. 










