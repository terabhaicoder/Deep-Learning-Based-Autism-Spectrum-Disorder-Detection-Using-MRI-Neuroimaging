# Deep Learning for Autism Detection Using MRI  

## Overview  
This project develops a deep-learning framework for early Autism Spectrum Disorder (ASD) detection using MRI neuroimaging. It integrates multiple datasets and leverages advanced preprocessing, augmentation, and transfer learning with CNN architectures (VGG19, ResNet50, InceptionV3).  

## Features  
- **MRI Preprocessing**: Resizing, normalization, and contrast enhancement.  
- **Data Augmentation**: Expands dataset using transformations.  
- **Deep Learning Models**: Uses pre-trained CNNs for feature extraction.  
- **Transfer Learning**: Enhances model generalization across datasets.  
- **Evaluation**: Compares model performance for ASD diagnosis.  

## Dataset  
- **Sources**: ABIDE
- **Data Types**: Structural and functional MRI scans  

## Model Architecture  
1. **Preprocessing**: Resizing (128×128×128), normalization, and contrast enhancement.  
2. **Data Augmentation**: Noise injection, rotation, flipping.  
3. **CNN Models**:  
   - VGG19  
   - ResNet50  
   - InceptionV3  
4. **Evaluation**: Performance comparison based on accuracy and loss.  

