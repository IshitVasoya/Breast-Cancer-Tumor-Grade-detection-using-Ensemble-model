Breast Cancer Tumor Grade Prediction

This repository implements a hybrid radiomics + deep learning pipeline to predict breast cancer tumor grade from MRI. It extracts handcrafted radiomic features and deep embeddings (via EfficientNetB7), selects key predictors, trains Random Forest and CNN classifiers, and ensembles their outputs for robust, interpretable grading.

Dataset

Duke Breast Cancer MRI (TCIA) – 925 patients
https://www.cancerimagingarchive.net/collection/duke-breast-cancer-mri (For this demo, we downloaded the first 100 patient folders.)
you have to download NBIA data retriver tool to download this dataset.


to run the model, first extract the zip file and then first run the Analyse_Dataset.ipynb file and then run the the Features Extractiona and model development_newVersion.ipynb file.
