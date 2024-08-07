# Real-Time Anomaly Segmentation for Road Scenes

## Overview
This project tackles the challenge of anomaly segmentation in real-world scenarios by building compact models capable of real-time deployment. Utilizing the Cityscapes dataset for training, we explore several baseline methods, including Maximum Softmax Probability (MSP), MaxLogit, and Max Entropy, using a pre-trained ERF-Net model. Additionally, we implement temperature scaling to assess the impact of the T parameter on out-of-distribution (OoD) object detection performance.
The models' performances are evaluated using metrics such as Area under the Precision-Recall Curve (AuPRC) and False Positive Rate at 95% True Positive Rate (FPR95). We also assess the models' capabilities for in-distribution object detection and image classification using mean Intersection over Union (mIoU). The results highlight the significant degradation in anomaly detection performance due to domain shift.

# Key Features

- Maximum Softmax Probability (MSP)
- MaxLogit
- Max Entropy

## Evaluation Metrics

* AuPRC (Area under the Precision-Recall Curve)
* FPR95 (False Positive Rate at 95% True Positive Rate)
* Mean Intersection over Union (mIoU)

## Results

+ The ERF-Net model performs well on in-distribution tasks.
+ Anomaly detection degrades significantly in domain shifts.
+ Temperature scaling had minimal impact on OoD detection.
