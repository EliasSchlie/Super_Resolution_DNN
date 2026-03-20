# Super-Resolution Using Deep Convolutional Networks

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)

Course project for Neural Networks for Data Science implementing the **RUNet** (Robust UNet) architecture for single-image super-resolution.

## Architecture

RUNet combines a U-Net encoder–decoder with residual connections to upsample low-resolution images while preserving fine detail.

![RUNet Architecture](https://raw.githubusercontent.com/cerniello/Super_Resolution_DNN/master/img/00_RUnet.png)

## Results

![](https://raw.githubusercontent.com/cerniello/Super_Resolution_DNN/master/img/results_1.png)
![](https://raw.githubusercontent.com/cerniello/Super_Resolution_DNN/master/img/results_2.png)
![](https://raw.githubusercontent.com/cerniello/Super_Resolution_DNN/master/img/results_3.png)

## Usage

Open `NN_Final_Project_3_Moschettieri.ipynb` in Jupyter or Google Colab. Requires TensorFlow.

## Reference

[Hu et al., "RUNet: A Robust UNet Architecture for Image Super-Resolution." CVPRW 2019](http://openaccess.thecvf.com/content_CVPRW_2019/html/WiCV/Hu_RUNet_A_Robust_UNet_Architecture_for_Image_Super-Resolution_CVPRW_2019_paper.html)
