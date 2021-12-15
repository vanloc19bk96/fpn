# Feature pyramid network

This repository is implemented from feature pyramid network
paper: [https://arxiv.org/pdf/1612.03144.pdf](https://arxiv.org/pdf/1612.03144.pdf)

<em>Note: This repository just implement model architecture. Not training, testing...</em>

## Introduction

Feature Pyramid Network (RPN) is a feature extractor designed for pyramid concept. It replaces the feature extractor of
detectors like Faster R-CNN and generates multiple feature map layers with better quality information than regular
feature pyramid for object detection.

<div align="center">

![feature pyramid network](resource/fpn.png "feature pyramid network")

</div>

## Run for testing

```
python fpn.py
```