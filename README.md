
# Cartonomics
This folder allows you to train/finetune models for symbol detection on old maps, primarily focusing on Cassini maps. Here, you will find all the processes to prepare and augment your data, as well as train, evaluate, and test your models.
## Table of Contents
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)
## Project Structure
The folder is organized as follows:
```plaintext
├── notebooks/                      # Folder to run notebooks 
│   ├── utils/                      # Utilities functions for the notebooks
│   ├── notebook1.ipynb
│   └── ...
├── models/                         # Folder containing modules for the training of different models
│   ├── detectron2/
│   ├── detr/
│   └── yolo/
├── Clusters/                       # Folder containing complete mosaics of clustering results
├── datasets/                       # Folder containing modules to prepare/augment the datasets
├── data/                           # Folder containing the datasets
├── outputs/                        # Folder with the weights of the different models
├── runs/                           # Folder with training/validation logs
├── tests/                          # Folder for testing different implementations
├───── requirements.txt
└───── README.md
```


