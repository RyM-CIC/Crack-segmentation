# Fully Convolutional Networks for Automatic Pavement Crack Segmentation
Pavement cracks are an increasing threat for public safety. Automatic pavement crack segmentation remains a very challenging problem due to crack texture inhomogeneity, high outlier potential, large variability of topologies, and so on. Due to this, automatic pavement crack detection has captured the attention of the computer vision community, and a great quantity of algorithms for solving this task have been proposed. In this work, we apply U-Net and two variants for automatic pavement crack detection. The main contributions of this research are: 1) we propose two U-Net based network variations for automatic pavement crack detection , 2) we perform several experiments to demonstrate that the proposed architectures outperform the state-of-the-art for automatic pavement crack detection using two public and well-known challenging datasets: CFD and AigleRN and 3) we provide the code for this approach. 


This repository includes the necessary files to execute the best segmentation model presented in the article, as well as the modified VGG16 model for segmentation.

The input images must be of size 320x480 and the ground true label must contain the segmented crack in a color format [255,0,255].

The programming of these FCNN was done using a GTX 980 TI GPU, using the Keras and TensorFlow libraries.

