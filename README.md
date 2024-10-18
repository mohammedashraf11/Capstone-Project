# Low Light Image Enhancement Using Retinex Theory
## Project Overview
This repository contains the implementation of a Low Light Image Enhancement algorithm based on Retinex Theory. The project aims to enhance images captured in low-light conditions by improving visibility, reducing noise, and preserving natural colors.

## Problem Statement
Low-light images often suffer from reduced visibility, high noise levels, and poor contrast. The goal of this project is to enhance these images by adjusting their illumination while preserving the natural appearance of objects. This enhancement is especially important for applications in photography, surveillance, and medical imaging.

## Objectives
* Enhance Low-Illumination Images: Improve the visibility and quality of low-light images.
* Preserve Natural Colors: Maintain the original color balance of the images.
* Reduce Noise: Minimize noise commonly found in low-light images.
## Methodology
### The project follows these steps for enhancing low-light images:

* Initial Light Estimation: Using Retinex theory, the environmental light component is estimated through a Gaussian filter.
* Iterative Refinement: The algorithm iteratively adjusts light and scattering parameters to optimize image visibility while preserving details.
* Weighted Guide Filter: This reduces common artifacts such as halos and block effects.
* Final Enhancement: Enhancements are applied to the intensity channel in the HSV color space to avoid color distortion.
## Tools Used
* MATLAB: Used for implementing the image processing algorithms.
* Retinex Theory: To separate illumination and reflectance components.
* Gaussian Filtering: For smoothing the illumination.
* Weighted Guide Filter: To minimize artifacts and improve the natural appearance of images.
## Features
* Brightness Enhancement: Increases overall brightness of low-light images.
* Noise Reduction: Enhances image clarity by minimizing noise.
* Edge Preservation: Maintains the sharpness of edges and details.
* Color Fidelity: Ensures that natural color balance is maintained during enhancement.
## Project Structure
* src/: Contains the MATLAB code for image enhancement.
* docs/: Contains the project report and supporting documentation.
* images/: Contains example images before and after enhancement.
* README.md: This file.
## Results
The project successfully enhances low-light images by improving visibility while maintaining natural colors and reducing noise. Compared to traditional methods like histogram equalization, this method achieves a better balance between brightness, noise reduction, and color fidelity.

## Future Work
* Integration with Deep Learning: Explore combining the Retinex model with deep learning for faster and more adaptive image enhancement.
* Real-Time Processing: Optimize the algorithm for real-time applications by improving computational efficiency.
* Video Enhancement: Extend the algorithm to enhance low-light videos, ensuring consistency across frames.
## Contributors
Mohammed Ashraf Razvi

Shaik Kashida Jabeen

Avva Praveen Babu

Under the guidance of **Pankaj Kandhway**, Assistant Professor.

