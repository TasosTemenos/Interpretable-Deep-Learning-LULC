# Interpretable Deep Learning Framework for Land Use and Land Cover Classification in Remote Sensing Using SHAP

This repository contains three Jupyter notebooks for analyzing the EuroSat dataset with different focuses: comprehensive analysis, remote sensing index analysis, and Near-Infrared (NRG) analysis. Results from the code have been published in the following paper: [Interpretable Deep Learning Framework for Land Use and Land Cover Classification in Remote Sensing Using SHAP](https://doi.org/10.1109/LGRS.2023.3251652).

## Notebooks

### 1. EuroSat_v3_ALL.ipynb
**Title**: EuroSat Dataset - Comprehensive Analysis
- **Description**: This notebook loads the EuroSat dataset and performs a comprehensive analysis, including data loading, splitting, and preparation for training machine learning models.
- **Key Steps**:
  1. Installation of `tensorflow_addons` and `shap`.
  2. Loading the entire EuroSat dataset using TensorFlow Datasets (TFDS).
  3. Extracting class names and the number of classes.
  4. Model training
  5. Model evaluation
  6. SHAP XAI visual results

### 2. EuroSat_v3_RS_Index.ipynb
**Title**: EuroSat Dataset - Remote Sensing Index Analysis
- **Description**: This notebook focuses on analyzing the EuroSat dataset with a specific emphasis on remote sensing indices. It includes steps for data loading, preparation, and analysis.
- **Key Steps**:
  1. Installation of `tensorflow_addons` and `shap`.
  2. Loading the EuroSat dataset using TensorFlow Datasets (TFDS), preparing it for remote sensing index analysis.
  3. Extracting class names and the number of classes.
  4. Model training
  5. Model evaluation
  6. SHAP XAI visual results

### 3. EuroSat_v3_NRG.ipynb
**Title**: EuroSat Dataset - Near-Infrared (NRG) Analysis
- **Description**: This notebook is dedicated to analyzing the EuroSat dataset with a focus on Near-Infrared (NRG) bands. It involves data loading, preparation, and specific analysis related to NRG.
- **Key Steps**:
  1. Installation of `tensorflow_addons` and `shap`.
  2. Loading the EuroSat dataset using TensorFlow Datasets (TFDS), preparing it for NRG analysis.
  3. Extracting class names and the number of classes.
  4. Model training
  5. Model evaluation
  6. SHAP XAI visual results

## Installation
To run these notebooks, you need to install the required libraries. You can do this by running the following commands:

```bash
pip install tensorflow_addons shap

## Cite

@ARTICLE{10057399,
  author={Temenos, Anastasios and Temenos, Nikos and Kaselimi, Maria and Doulamis, Anastasios and Doulamis, Nikolaos},
  journal={IEEE Geoscience and Remote Sensing Letters}, 
  title={Interpretable Deep Learning Framework for Land Use and Land Cover Classification in Remote Sensing Using SHAP}, 
  year={2023},
  volume={20},
  number={},
  pages={1-5},
  keywords={Remote sensing;Convolutional neural networks;Correlation;Additives;Deep learning;Crops;Standards;Convolutional neural network (CNN);EuroSAT;explainable AI (XAI);land cover;land use;remote sensing;Shapley additive explanation (SHAP)},
  doi={10.1109/LGRS.2023.3251652}}

