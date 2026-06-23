# Image-processing
This repository contains several computer vision and image processing projects implemented in Python, OpenCV, PyTorch, and Google Colab.

## Projects

### 1. YOLOv5m Object Detection

This notebook demonstrates object detection using the YOLOv5 Medium (YOLOv5m) model. Pretrained COCO weights are used to identify and localize objects in street scenes, including pedestrians, vehicles, bicycles, and motorcycles. The project supports both image and video inputs and allows confidence threshold adjustment and class-specific detection.


### 2. Brain_tumor_roboflow

This project applies YOLOv7 object detection to identify brain tumors in MRI images. A custom dataset obtained from Roboflow was used for training and evaluation. The notebook covers the complete deep learning pipeline including dataset loading, model training, validation, inference on unseen images, and performance assessment through confusion matrix analysis.


### 3. MRI_De_Noising:
This project implements and compares several image denoising techniques, including Gaussian, bilateral, total variation, wavelet, anisotropic diffusion, non-local means, and BM3D filtering, applied to noisy MRI images. Each method is evaluated using Peak Signal-to-Noise Ratio (PSNR) to measure reconstruction quality against a clean reference image. The results highlight the trade-offs between noise removal and detail preservation, finding the best method for medical imaging


### 4. Scikit_image
This notebook demonstrates a wide range of fundamental image processing techniques using scikit-image & numpy including grayscale conversion, histogram analysis, thresholding, edge detection, filtering, morphological operations, and geometric transformations. It also covers advanced tasks such as image restoration, segmentation (SLIC), contour detection, corner detection, and face detection. The goal is to provide a hands-on understanding of how different algorithms affect image structure, contrast, and feature extraction in real-world computer vision tasks.


### 5. Brain_MRI_Segmentation_Unet
This project demonstrates a deep learning approach for brain tumor segmentation using the LGG MRI dataset from Kaggle. A U-Net architecture is trained on paired MRI images and masks with real-time data augmentation to improve generalization. The model is evaluated using accuracy and loss metrics, and predictions are visualized to compare ground truth masks with generated segmentation results.


### 6. Brain_Tumor_Segmentation_Mask R-CNN

Developed a deep learning pipeline for automatic brain tumor segmentation in MRI images using Mask R-CNN. The model was trained on a custom dataset with polygon-based tumor annotations to perform accurate pixel-level tumor localization and segmentation. The project includes dataset preparation, custom data loading, model training, inference, and visualization of predicted tumor masks, enabling automated identification and analysis of tumor regions in brain MRI scans.

