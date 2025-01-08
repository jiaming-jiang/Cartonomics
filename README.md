
# Cartonomics
For final deliverables, please find the project report in the `Report` folder; main scripts in the `notebooks` folder; fine-tuned model in the `outputs` folder; and the posterior classification results in the `Clusters` folder.

Due to the large size of the datasets (including the multiple crop-augmented ones), it is not feasible to upload it here.

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
├── tests/                          # Folder for testing different implementations
├───── requirements.txt
└───── README.md
```


