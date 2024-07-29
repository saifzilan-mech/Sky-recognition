# Pattern Recognition for Sky Recognition

## Overview

This project focuses on predicting the time of day from images of the sky using advanced pattern recognition techniques. By analyzing the color and texture changes in the sky throughout the day, the project aims to accurately classify the time of the image capture.

## Objectives

- Develop algorithms for sky recognition to predict the time of day.
- Use Principal Component Analysis (PCA), Gaussian Mixture Models (GMM), and Convolutional Neural Networks (CNN) for image processing and classification.
- Acquire and preprocess sky images for accurate analysis.

## Methodology

### Data Acquisition
- Sky images were captured using smartphone cameras at four different times of the day: 8 AM, 12 PM, 4 PM, and 8 PM.
- Images were taken on consecutive days to ensure consistency and minimize the impact of changing lighting conditions.

### Data Preprocessing
- Cropped image boundaries to homogenize sky color.
- Generated random patches from images to expand the dataset and improve model performance.

### Algorithms
- **PCA and GMM**: Used PCA for dimensionality reduction and GMM for clustering and initial classification.
- **CNN**: Implemented a CNN for more accurate image classification, using techniques like data augmentation to enhance model robustness.

### Model Training and Evaluation
- Split the dataset into training and testing sets.
- Applied data augmentation techniques to improve model generalization.
- Trained the CNN model with layers for convolution, activation (ReLU), pooling (MaxPooling), and dense classification.

## Results

- The PCA and GMM approach identified general patterns but showed limited accuracy.
- The CNN model, particularly with data augmentation, provided more robust and accurate classification of sky images, successfully predicting the time of day with significant accuracy improvements over PCA and GMM alone.

## Future Work

- Increase the number of images taken at the same times to capture more data variations.
- Explore additional approaches beyond RGB channels for sky pattern recognition.
- Enhance the CNN model further with more sophisticated architectures and training techniques.

## References

- Alkandari, A., & Aljaber, S. J. (2015). Principle component analysis algorithm (PCA) for image recognition. 2015 Second International Conference on Computing Technology and Information Management (ICCTIM), 76–80. https://doi.org/10.1109/ICCTIM.2015.7224596
- Chauhan, R., Ghanshala, K. K., & Joshi, R. C. (2018). Convolutional neural network (CNN) for image detection and recognition. 2018 First International Conference on Secure Cyber Computing and Communication (ICSCCC), 278–282. https://doi.org/10.1109/ICSCCC.2018.8703316
- Feng, M. C. (2017). Short-term global horizontal irradiance forecasting based on sky imaging and pattern recognition (IEEE). https://doi.org/10.1109/PESGM.2017.8274480
- Calbó, J. S. (2008). Feature extraction from whole-sky ground-based images for cloud-type recognition. Journal of Atmospheric and Oceanic Technology, 3–14. https://doi.org/10.1175/2007JTECHA959.1

