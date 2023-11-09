# An Ensemble of UNet Frameworks for Lung Nodule Segmentation

![Conference](https://img.shields.io/badge/Conference-APAMCS%202022-blue)
![Published In](https://img.shields.io/badge/Published%20In-Springer%20LNNS-green)
![DOI](https://img.shields.io/badge/DOI-10.1007%2F978--3--031--34127--4__44-blue)

This repository contains the implementation details and results of the paper "An Ensemble of UNet Frameworks for Lung Nodule Segmentation", which has been accepted at the International Conference on Actual Problems in Applied Mathematics and Computer Science 2022 (APAMCS 2022) and published in the "Current Problems in Applied Mathematics and Computer Science and Systems", part of the Lecture Notes in Networks and Systems series by Springer.

## Table of Contents
- [Authors](#authors)
- [Publication](#publication)
- [Abstract](#abstract)
- [Code](#code)
- [Usage](#usage)
- [Citation](#citation)

## Authors

- [Nandita Gautam](https://www.linkedin.com/in/nandita-gautam-a7932b95/) 
- [Abhishek Basu](https://www.linkedin.com/in/iabhishekbasu/) 
- [Dmitry Kaplun](https://etu.ru/en/educators/persons/dmitry-i-kaplun)
- [Ram Sarkar](http://www.jaduniv.edu.in/profile.php?uid=686)

## Publication

The paper is available at: [Springer Link](https://doi.org/10.1007/978-3-031-34127-4_44)

## Abstract

One of the most common types of cancer in the world is lung cancer, which is a cause of increasing mortality. It is most often discovered in the middle and later stages as it does not have obvious symptoms due to which its treatment is often missed. Studies show that most lung cancers are in the form of lung nodules, which can be categorized as benign or malignant. Thus, accurate early identification of malignant lung nodules that might later become cancerous is essential for the prevention of lung cancer. Computed Tomography (CT) images can be useful for identifying and segmenting these nodules. In this paper, we propose an ensemble model, called BUS-UNet++, to segment lung nodules using CT images. We use a combination of the ConvLSTM up-sampling architecture from BUS-UNet and skip connections in aggregation blocks from the UNet++ model to build the BUS-UNet++ ensemble. The dataset for this study is collected from the Lung Image Database Consortium Image Database Resource Initiative (LIDC-IDRI), where we have selected the modality of these images as CT images. These are further preprocessed to obtain nodule masks and nodule images, which constitute the Region of Interest (RoI). The accuracy achieved with the Adam Optimizer is 0.9731, the Intersection over Union (IoU) of about 0.8439, and the dice score coefficient (DSC) of about 0.958 are obtained by the proposed system. This ensemble model outperforms several state-of-the-art models used for the same purpose.

## Code


## Usage


## Citation

If you find our work useful in your research, please consider citing:

```bibtex
@InProceedings{10.1007/978-3-031-34127-4_44,
  author    = {Gautam, Nandita and Basu, Abhishek and Kaplun, Dmitry and Sarkar, Ram},
  editor    = {Alikhanov, Anatoly and Lyakhov, Pavel and Samoylenko, Irina},
  title     = {An Ensemble of UNet Frameworks for Lung Nodule Segmentation},
  booktitle = {Current Problems in Applied Mathematics and Computer Science and Systems},
  year      = {2023},
  publisher = {Springer Nature Switzerland},
  address   = {Cham},
  pages     = {450--461},
  isbn      = {978-3-031-34127-4}
}

