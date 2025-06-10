# MCoCoNet-main

This project provides the code and results for 'Multi-Channel Aligned Feature Fusion Method for Salient Object Detection in Optical Remote Sensing Images'
# Network Architecture
   <div align=center>
   <img src="https://github.com/winnieZ17/MCoCoNet-main/blob/main/images/MCoCoNet.png">
   </div>
   
   
# Requirements
   python 3.10 + pytorch 2.0.0


# Saliency maps
   We provide saliency maps of our MCoCoNet on four datasets in /datasets.


# Training

python train.py.

For MCoCoNet_VGG, please modify paths of VGG backbone in MCoCoNet/model/vgg.py.

data_aug.m is used for data augmentation.


# Pre-trained model and testing
1. The following pre-trained models and put them in MCoCoNet/models.

2. Modify paths of pre-trained models and datasets.

3. Run test.py.

   
# Evaluation Tool
   You can use the evaluation tool in /evaluation/main.py to evaluate the above saliency maps.
