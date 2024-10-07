# Image Processing Task: Operations

## Project Description

This project involves applying fundamental image processing techniques using Python. I worked with a provided image and performed a series of operations such as loading, converting to grayscale, resizing, cropping, normalizing, augmenting, and reducing noise, essential for preparing images for further processing in real-world applications like machine learning, computer vision, and data preprocessing.

## Table of Contents

- [Installation](#installation)
- [Loading and Reading the Image](#loading-and-reading-the-image)
- [Converting to Grayscale Color Channel](#converting-to-grayscale-color-channel)
- [Resizing the Image](#resizing-the-image)
- [Cropping the Image](#cropping-the-image)
- [Normalizing Pixel Values](#normalizing-pixel-values)
- [Data Augmentation](#data-augmentation)
- [Noise Reduction](#noise-reduction)
- [Libraries and Tools Used](#libraries-and-tools-used)

### Installation:

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/a-r-p-i-t/Computer-Vision-Task.git

2. **Download the ipynb file**:
    <br>
  **[Computer_Vision_Task_Arpit_Mohanty.ipynb](./Computer_Vision_Task_Arpit_Mohanty.ipynb)**

4. **Install required packages**:
   ```bash
   !pip install -r requirements.txt

### Operations to be Performed:

1. ### Loading and Reading the Image
   Loading the provided image using Open-Cv Library.

2. ### Converting to Grayscale Color Channel
   Converting it to grayscale using methods such as averaging or weighted averaging to simplify the image and reduce dimensionality.

3. ### Resizing the Image
   Resizing the image to a uniform size while maintaining the aspect ratio to avoid distortion. I used interpolation method of Linear Interpolation to fill in pixel values during resizing.

4. ### Cropping the Image
   I cropped the image around the centre.

5. ### Normalizing Pixel Values
   Normalizing the pixel values to a specific range (0-1 ) for improved numerical stability in image processing pipelines. Normalized using the mean and standard deviation of the dataset.

6. ### Data Augmentation
   Applied transformations to generate new variations of the image and expand the dataset. Augmented the image with techniques such as flipping, rotating, shearing, zooming, and adding noise.

7. ### Noise Reduction
   Reducing noise in the image by applying filters such as Gaussian blur.

### Libraries and Tools Used

- **OpenCV**
- **NumPy**
- **imgaug**


