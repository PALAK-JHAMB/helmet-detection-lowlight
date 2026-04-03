# Low-Visibility Helmet Detection
## Problem Statement 2 — Generative AI for Safety Monitoring

## Pipeline
Dark/Hazy Image → Zero-DCE Enhancement → YOLOv8 Detection

## Results
- YOLOv8n mAP@50     : 0.629
- Helmet class mAP@50: 0.948
- Head class mAP@50  : 0.913
- Enhancement Model  : Zero-DCE (10 epochs)

## Dataset
Hard Hat Workers — Roboflow (5269 images, 3 classes)

## Classes
head, helmet, person
