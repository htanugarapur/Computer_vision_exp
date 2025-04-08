# 🧠 Computer Vision Lab Experiments

Welcome to the **Computer Vision Lab Experiments** repository!  
This repo contains **computer vision experiments** demonstrating fundamental and advanced techniques in **digital image processing and computer vision**, implemented in Python using **OpenCV**, **NumPy**, and **Matplotlib**.

Explore edge detection, feature extraction, filtering, image segmentation, and more – all with practical notebooks and real input images.

---

## 🧪 Experiments Overview

| # | Notebook | Description |
|--:|----------|-------------|
| 1 | **Image_Processing_Techniques.ipynb** | Core operations like grayscale conversion, thresholding, smoothing, sharpening, and intensity transformations. |
| 2 | **Colour_Modules.ipynb** | Color space transformations (RGB ↔ HSV, CMY), channel manipulations, and visualizations. |
| 3 | **Image_Transformation.ipynb** | Affine transforms, scaling, rotation, translation, perspective warps. |
| 4 | **DFT_Histogram_and_Linear_Filtering.ipynb** | Discrete Fourier Transform (DFT), histogram equalization, and spatial domain filtering. |
| 5 | **Canny_Edge_Detection_LOG_and_DOG.ipynb** | Multi-method edge detection: Canny, Laplacian of Gaussian (LoG), and Difference of Gaussian (DoG). |
| 6 | **Noise_Restoration_and_Filters.ipynb** | Adding noise (Salt & Pepper, Gaussian), and applying smoothing/median/bilateral filters for restoration. |
| 7 | **Roberts_and_Prewitt_Filters.ipynb** | Classic edge detectors: Roberts and Prewitt operators in gradient-based edge detection. |
| 8 | **Hough_and_Harris_Detection.ipynb** | Line detection via Hough Transform and corner detection using the Harris method. |
| 9 | **GLOH_HOG_DOG_SIFT_ORB.ipynb** | Advanced feature detectors & descriptors: GLOH, HOG, SIFT, ORB, and DoG. |
|10 | **Segmentation.ipynb** | Image segmentation using thresholding, region growing, contour extraction, and possibly watershed. |
|11 | **bgextractcv.ipynb** | Video background and foreground extraction, and icluded the motion detection. |

---

## 🖼️ Some Input Images

The following sample images are used across various experiments for testing and demonstrations:

- `ash.png`
- `ashgoh.png`
- `df.png`
- `nikolatesla.png`
- `ww.jpg`

You can try your own images by replacing these or uploading additional ones to the notebooks.

---



## 📦 Prerequisites

Make sure you have the following Python libraries installed:

```bash
pip install numpy opencv-python matplotlib scikit-image
