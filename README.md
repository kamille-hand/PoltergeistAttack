# What is DolphinAttack?

## How does DolphinAttack work?

# Simulation Evaluation

## Blur moodel
  Adversarial blurry images are generated by our blur model with public autonomous driving image datasets as input. Our blur model can be used as a function in `blur.py`

## Datasets
  We use two autonomous driving datasets BDD100K and KITTI in the simulation evaluation. For both datasets, we randomly select 200 images for evaluation.
  The pictures that we selected 

## Object Detectors
We evaluate PG attacks using four academic object detectors YOLO V3/V4/V5 and Faster R-CNN, and one commercial object detector YOLO 3D used in Apollo.
The backbone networks used for the pre-trained models YOLO V3/V4/V5 and Faster R-CNN are Darknet-53 and ResNet-101, respectively. The four academic detectors are all trained on the Common Objects in Context (COCO) dataset and Apollo is trained on an unrevealed backbone network and dataset.

## Bayesian Optimization
To optimize the designed objective functions, we employ Bayesian Optimization, a sequential design strategy for global optimization of blackbox functions that does not assume any functional forms.




