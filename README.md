# vehicle_reID
## Introduction
Vehicle ReID baseline is a pytorch-based baseline for training and evaluating deep vehicle re-identification models on reid benchmarks.

## Datasets
+ [veri776](https://github.com/VehicleReId/VeRidataset)

## Models
+ resnet50
## Losses
+ cross entropy loss
+ triplet loss

## Results
Some test results on veri776:

### the result of one of the methods of training
model:resnet50 

loss: xent+htri

| mAP | rank-1 | rank-5 | rank-20 |
|:---:| :----: | :----: | :-----: |
|59.0|87.6|94.3|98.2|
