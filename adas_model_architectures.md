# ML Model Architectures for ADAS

## Perception Models:
- CNN (ResNet, YOLO, MobileNet) – for object detection & segmentation
- Vision Transformer (ViT) – for advanced scene understanding

## Temporal Models:
- RNN / LSTM – for time-series sensor data (e.g., drowsiness detection)
- GRU – for lightweight sequence modeling
- Transformers – for large-scale fusion

## Fusion Models:
- Multi-stream CNN + RNN – for camera + radar fusion
- Late Fusion using FC layers – combining decisions from multiple models

## Deployment Targets:
- Qualcomm Snapdragon SoCs (GPU, DSP)
- QNX / Linux / Android Embedded