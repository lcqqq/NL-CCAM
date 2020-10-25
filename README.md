# NL-CCAM
Combinational Class Activation Maps for Weakly Supervised Object Localization

https://openaccess.thecvf.com/content_WACV_2020/papers/Yang_Combinational_Class_Activation_Maps_for_Weakly_Supervised_Object_Localization_WACV_2020_paper.pdf

# Environments

python == 3.6

pytorch == 0.4.0

opencv == 3.4.2

# Dataset

CUB-200-2011

PATH: ./CUB_200_2011

# Pre-trained model

VGG16 pretrained on ImageNet

NL-CCAM for CUB-200-2011

# Training and Test for your own model


Change codes for your model

Training: train_cub.py
1. model
2. dataloader

Evaluating: IoU_check_cub_5.py
1. load model
2. choose function for CCAM

# Get the paper results

For getting bounding boxes, we should use a threshold value.

I fix the threshold value for quadratic function.

You can change threshold values for the best results of your models.
