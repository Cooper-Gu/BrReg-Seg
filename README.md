# BrReg-Seg
The code for **BrReg-Seg: A Framework for Fast Multi-modal Stroke Lesion MR Image Segmentation**.

# Prerequisites
Python 3.7.1+

Pytorch 1.7.0+

SimpleITK

This code has been trained and inferred with Pytorch 1.13.1 and NVIDIA 3090Ti GPU.

 # Description
The BrReg-Seg framework contains two parts of the network, one of which is the unsupervised alignment model ConvNXMorph, and the other is nnUNet-v2. The framework code is now open.

BrRegSeg_b indicates a network with bi-channel inputs.

BrRegSeg_t indicates a network with three-channel inputs.

All codes are open after the paper is accepted.

 # Acknowledgment
Some codes in this repository are modified from [TransMorph](https://github.com/junyuchen245/TransMorph_Transformer_for_Medical_Image_Registration) and [nnUNet-v2](https://github.com/MIC-DKFZ/nnUNet).

lf you have any questions, please feel free to ask, I am more than happy to help.
