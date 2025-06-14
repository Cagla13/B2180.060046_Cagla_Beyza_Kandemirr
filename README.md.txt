UYG332 - Image Processing Final Project
 Student Info
- Name: Çağla Beyza Kandemir  
- Student ID: B22180.060046 


PROJECT SUMMARY

There are 5 image processing exercises using OpenCV, NumPy, and Matplotlib in this notebook. Each section was run step by step using Python, along with visual and statistical outcomes.

STEP 1 – Drawing Rectangle and RGB Image
An image was read, converted from BGR to RGB, and a 30x40 colored rectangle at the middle was drawn with OpenCV. The operation was confirmed by checking the color value at the middle pixel.

 STEP 2 – Negative Transformation
A gray-scale image was read in and its negative created using `255 - image`. The operation was verified by examining pixel values prior to and following inversion.

 STEP 3 – Logarithmic and Inverse Log Transformation
Inverse log and log transforms were utilized to explore brightness intensification. It was seen how log functions have the ability to brighten dark areas and alter contrast.

STEP 4 – Applying Unsharp Masking (Spatial and Frequency Domains)
Two techniques were used to enhance the moon photograph:
- Spatial domain: Gaussian blur + edge mask
- Frequency domain: High-pass filter + Fourier transform
Three different values of `k` (0.5, 1.0, 1.5) were employed for comparing the sharpening intensity.

STEP 5 – Denoising Filters Application to PCB Images
Salt-and-pepper noise was detected using visual cues and histogram. Three filters were tested:
- Median Filter: Most effective, preserved edges
- Gaussian Filter: Blurred details but smoothed image

- Bilateral Filter: Balanced result but not as clean as median

Statistics:

- Median → Mean: `129.44`, Variance: `687.23`

- Gaussian → Mean: `127.92`, Variance: `590.76` 

 Conclusion Of all the filters and methods attempted, the Median filter gave the cleanest output for noisy images, and spatial unsharp masking was simpler and more intuitive than frequency-based sharpening. Each part of the project allowed me to discover basic image processing concepts by getting my hands dirty.