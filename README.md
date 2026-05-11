# CUB-200-2011 Bird Species Classification

Author: Affan Ahmed

## Overview
Fine-grained visual classification of 200 bird species using EfficientNetV2-S on the CUB-200-2011 dataset.

## Dataset
- 11,788 images
- 200 bird species
- Dataset: Caltech-UCSD Birds 200-2011

## Model
- EfficientNetV2-S (timm pretrained)
- Two-stage transfer learning

## Techniques Used
- Bounding box cropping
- Label smoothing
- AdamW
- Cosine Annealing LR
- Mixed Precision Training
- Data Augmentation

## Results
- Top-1 Accuracy: 78.12%
- Top-5 Accuracy: 94.70%

## Future Improvements
- MixUp / CutMix
- Test Time Augmentation
- Progressive resizing
