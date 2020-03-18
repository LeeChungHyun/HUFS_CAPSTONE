# HUFS_CAPSTONE
HUFS Capstone Project 

## Self_Checkout_Platform
```
점원 없이 상품이 무엇인지 인식하는 플랫폼을 만든다.
```
--------------------------

## Environment
```
Ubuntu 18.04, Python, OpenCV, Tensorflow
```
------------------

## Technology
```
Object Detection + Recognition
Network = Faster_R_CNN
```
------------------

## Procedure
```
Data Labeling(LabelImg program) --> Data Augmentation(ImgAug) --> Tensorflow Object Detection API --> TFRecord --> Configuration --> Transfer Learning(Resnet101_coco, Inception_v2_coco)
```
