
# Cartonomics
This project is based on the previous work from [COCASS](https://github.com/CRH-EHESS/cocass-benchmarking/tree/main) and this repository is forked from it. 

For our final deliverables, please find the project report in the `Report` folder; main scripts in the `notebooks` folder; fine-tuned model in the `outputs` folder; and the posterior classification results in the `Clusters` folder.

Due to the large size of the datasets (including the multiple crop-augmented ones), we could not upload them here.

## Project Structure
The repository is organized as follows:
```plaintext
├── notebooks/                      # Folder to run notebooks 
│   ├── utils/                      # Utilities functions for the notebooks
│   ├── yolo_training.ipynb         # Tuning experiments on detection
│   ├── clustering.ipynb            # Posterior classification
│   └── ...
├── Clusters/                       # Complete mosaics of clustering results
├── Report/                         # Final report and source zip file
├── outputs/                        # Best model weight and training logs
│
│
├── models/                         # Folder containing modules for the training of different models
├── datasets/                       # Folder containing modules to prepare/augment the datasets
├── data/                           # Folder containing the datasets
├───── requirements.txt
└───── README.md
```


