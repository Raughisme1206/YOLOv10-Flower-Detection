# YOLOv10n Specific Flower Object Detection

## Project Overview

This project implements a lightweight object detection system for specific flower categories using YOLOv10n. The model is trained on a Roboflow flower detection dataset and tested on custom flower images.

## Project Title

**Specific Flower Object Detection and Edge Computing Performance Analysis Using YOLOv10n**

## Dataset

The dataset is collected from Roboflow Universe and contains three flower classes:

- Dianthus
- Rose
- Supannika flower

## Model

- Model: YOLOv10n
- Task: Object Detection
- Platform: Google Colab
- Framework: Ultralytics YOLO

## Features

- Train YOLOv10n on a custom flower dataset
- Detect specific flower types in uploaded images
- Display bounding boxes and confidence scores
- Count detected flower types
- Calculate flower type ratio
- Evaluate edge computing metrics such as model size, inference time, and FPS

## Results

The model was evaluated using the following metrics:

- box_loss
- cls_loss
- dfl_loss
- precision
- recall
- mAP50
- mAP50-95

## Limitations

The model is limited to the flower categories included in the dataset. It may not correctly detect unseen flower species such as tulips, sunflowers, or daisies. The detection performance may also decrease in dense flower field images or complex backgrounds.

## Edge Computing Evaluation

The trained YOLOv10n model is lightweight and suitable for edge AI experiments. The evaluation includes:

- Model size
- Inference time
- Estimated FPS

## Future Work

- Collect more flower images
- Increase dataset diversity
- Add more flower species
- Test YOLOv8n, YOLOv10n, and YOLO11n
- Export the model to ONNX for edge deployment
