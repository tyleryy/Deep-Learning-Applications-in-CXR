The notebook is split into two main sections: the experiments for the CheXpert test dataset and the COVIDx CXR-4.

CheXpert:
1. Mount Drive section: mounts google drive files and installs necessary dependencies as well as configure path to CheXpert dataset in Google drive
2. Deleting DS files: only run if DS files exist from a local download on Mac
3. Run the Dataset, Dataloaders, and models with specified hyperparameters
4. Run the training loop with specified early stopping parameters
5. Run Evaluation block to see confusion matrix and evaluation metrics

Covidx CXR-4:
1. Setup: install dependencies, set seed, use GPU or CPU, download Kaggle dataset, and set up dataframes
2. Run dataset dataset, dataloaders, and sampler code, and model setup (tuning hyperparameters of loaders and models & sampling size of subset sampler)
3. Run the train loop
4. Evaluate the results of model to see the epoch loss and accuracy curves on the validation and training datasets
5. "Transformers Ensemble!" section: use pretrained weights to load models for ensemble (can be found in project google drive folder: https://drive.google.com/drive/folders/1VQ6VHVB-0Rp-mDzUzHl15XpnRMNCuULj?usp=sharing)
