<div align="center">

# ON THE CLOUD DETECTION FROM BACKSCATTERED IMAGES GENERATED FROM A LIDAR-BASED CEILOMETER: CURRENT STATE AND OPPORTUNITIES
Alessio Barbaro Chisari, Alessandro Ortis, Luca Guarnera, Wladimiro Carlo Patatu, Rosaria Ausilia Giandolfo, Emanuele Spampinato, Sebastiano Battiato, Mario Valerio Giuffrida

[![Conference](https://img.shields.io/badge/ICIP-2024)]

</div>


# CeilometerDatasetBenchmark
This repository contains the code to generate the benchmark needed to evaluate five state-of-the-art models (**EfficientNet**, **Inception v3**, **ResNet50**, **VGG16** and **ViT**) on the binary classification task regarding cloud detection using a new dataset: the Ceilometer measurements dataset, released together with the bechmark data. 
The structure of the repository is as follows: each model has a folder containing two subfolders: SGD and Adam (one for each optimizer proposed in the experiments).
Each subfolder contains seven Jupyter Notebooks, organized as follows:
  - For SGD:
      - 1- lr=1e-3, momentum=0.9, weight_decay=1e-4
      - 2- lr=1e-4, momentum=0.8, weight_decay=1e-5
      - 3- lr=1e-5, momentum=0.7, weight_decay=1e-6
      - 4- lr=1e-6, momentum=0.9, weight_decay=1e-6
      - 5- lr=1e-2, momentum=0.9, weight_decay=1e-3
      - 6- lr=1e-2, momentum=0.8, weight_decay=1e-2
      - 7- lr=1e-2, momentum=0.8, weight_decay=1e-4
  - For Adam:
      - 1- lr=1e-3, weight_decay=1e-4
      - 2- lr=1e-4, weight_decay=1e-5
      - 3- lr=1e-5, weight_decay=1e-6
      - 4- lr=1e-6, weight_decay=1e-6
      - 5- lr=1e-2, weight_decay=1e-3
      - 6- lr=1e-2, weight_decay=1e-2
      - 7- lr=1e-2, weight_decay=1e-4
# Usage
- 1- Download the dataset from the following link: https://zenodo.org/records/10616434.
- 2- Upload the dataset on your Google Drive.
- 3- Load the .ipynb notebook on Google Colaboratory, and you will be able to run the cells.
- 4- Adapt all the paths contained in the code with your own.
# License
All the code is under the CC BY-NC-SA 2.0 Generic License.
Please cite our work for any use of the dataset or code in this repository using this citation: 

@inproceedings{chisari2024,
  author       = {Alessio Barbaro Chisari and others},
  title        = {On the Cloud Detection from Backscattered Images Generated From a Lidar-Based Ceilometer: Current State and Opportunities},
  booktitle    = {{IEEE} {ICIP} 2024,
                  Abu Dhabi, UAE, October 27-30, 2024},
  year         = {2024}
}

# Contacts
Alessio B. Chisari - alessio.chisari@phd.unict.com
