# Object Detection Project

Welcome to the Object Detection Project! In this tutorial, we focus on the task of object detection using YOLOv5 model. We'll cover data preparation, model training, evaluation, and analysis to achieve accurate detection results.

## Task Overview

### 0. Data Preparation
   - Download the SVHN Dataset in YOLO format.
   - Split the dataset into train, validation, and test sets.
   - Initialize [Weights & Biases (WandB)](https://docs.wandb.ai/quickstart) for experiment tracking.

### 1. Fine-tuning an Object Detector
   - Train a YOLOv5 model using pre-trained weights from a specified repository.
   - Log training progress with WandB.
   - Evaluate the model's performance on the test set:
     - Report class-wise IoU, mean IoU (mIoU), Average Precision (AP), and mean Average Precision (mAP).
     - Plot Precision-Recall (PR) curve.
   - Report performance metrics using AP@[0.50:0.5:0.95], AP50, and AP75.

### 2. Data Augmentation Techniques
   - Apply suitable data augmentation techniques to enhance model generalization.
   - Train the object detection model with augmented data.
   - Report performance metrics including IoU, AP, and mAP on the test set.


## Highlights
- **YOLOv5 Model:** Train an object detector using YOLOv5 model.
- **Performance Evaluation:** Assess model performance with class-wise IoU, mIoU, AP, mAP, and PR curve.
- **Data Augmentation:** Utilize data augmentation techniques for improving model robustness.

Stay tuned for updates and insights as we explore the fascinating world of object detection!

