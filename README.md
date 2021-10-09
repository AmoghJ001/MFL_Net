# MFL-Net: A Lightweight Multi-Scale Feature Learning Network For COVID-19 Diagnosis From Chest Radiography Scans
This repository contains the MFL_Net code. The model was trained on two datasets:<br/>
1) COVID-CT Dataset<br/>
2) SARS-CoV-2 CT Scan Dataset<br/>

![IMG](./Img/mfl-final.jpg)
Illustration of the proposed multi-scale feature learning (MFL) block. It consists of five convolutional layers with 3  3 filters and residual
connections to capture features with various sizes receptive fields (i.e., multi-scale features). The 11 convolutional layers are used to reduce the
number of channels in the feature maps

![IMG](./Img/model-final.jpg)
The overall architecture of the proposed MFL-Net. It consists of four MFL blocks; each follows a max-pool layer. The output of the last MFL
block is fed to a global average pooling (GAP) layer and a classification layer to classify each input image as COVID-19 or Non-COVID-19.
