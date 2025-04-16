# Skin-Cancer-Classification
This repository contains personal work towards an ongoing team project at university. 

My part for the initial phase focused on the implementation of DenseNet-121, DenseNet-169, and DenseNet-201 for classifying skin lesions as benign or malignant using the ISIC Archive dataset. I developed these densely connected convolutional networks in PyTorch, leveraging their skip connections to enhance feature reuse and mitigate vanishing gradients, achieving a test accuracy of 74.26% with DenseNet-169 outperforming the others (AUC 0.83). My work involved preprocessing 18,000 dermoscopic images, fine-tuning pre-trained models with a sigmoid-activated output layer, and optimizing with Adam and BCEWithLogitsLoss.
