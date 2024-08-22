# Polyp Segmentation use my model in Kvasir SEG Dataset
## Overview
This repository contains the implementation of binary segmentation models for detecting polyps in small intestine images. The project leverages the Kvasir dataset, which provides a rich collection of annotated endoscopic images. Accurate segmentation of polyps is crucial for early diagnosis and treatment of gastrointestinal diseases.

## Project Description 
Binary segmentation of small intestine polyps is a crucial task in medical image analysis, aiming to accurately delineate polyp regions from endoscopic images. Using the Kvasir-SEG dataset, which contains high-quality annotated images of various polyp types, we focus on developing deep learning models that can efficiently segment polyps from the surrounding tissue. The challenge lies in handling the diverse appearance, size, and shape of polyps, as well as variations in image quality and lighting conditions. By employing advanced neural network architectures and techniques such as data augmentation, we strive to enhance the model's generalization capability, leading to precise and reliable segmentation results that can aid in the early detection and treatment of gastrointestinal diseases.

## Dataset
- **Dataset**: Kvasir SEG
- **Description**: The Kvasir dataset includes a variety of annotated images from gastrointestinal examinations. For this project, we focus on the polyp images, where each image is paired with a ground truth mask indicating the polyp region.

## Approach
- The approach involves training deep learning models to perform binary segmentation of polyps in the provided images. The models are evaluated based on metrics like Dice coefficient, Intersection over Union (IoU), and Accuracy to ensure reliable segmentation results.

## Booster Net Architecture

![Booster_Net](https://github.com/user-attachments/assets/408301a9-e29e-43de-ab98-ac1f69e191b0)

## Residual Block

![Residual_Block](https://github.com/user-attachments/assets/190be075-ba6e-41b1-8146-bf246f5c57d6)


## Bottle and Inverted Residual Block

![Bottle_Inverted_Residual_Block](https://github.com/user-attachments/assets/a770b534-b0bd-4843-89d5-9829020b1e0e)


## Wide Vision Block

![Wide_Vision_Block](https://github.com/user-attachments/assets/5de2867a-11ff-4c62-8cdc-62dae308e580)

## Booster Block

![Booster_Block](https://github.com/user-attachments/assets/44dcd9c5-2b7b-447a-820e-2890adb17e1d)

## Result
- **Booster Net** : Dice Coefficent, Jaccard Index (IoU) and Accuracy Metric

![image](https://github.com/user-attachments/assets/b757c5e6-d571-42ed-8615-a809f212151b)

- **Image Segmentation** : The images segmentation use DCGC Deep Net

![image](https://github.com/user-attachments/assets/5c42411a-c6da-430f-87e4-f56750c79640)

## Table Comparing 

| Model | Dice Coefficient | Jaccard Index (IoU) |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
| Row 3, Col 1 | Row 3, Col 2 | Row 3, Col 3 |
