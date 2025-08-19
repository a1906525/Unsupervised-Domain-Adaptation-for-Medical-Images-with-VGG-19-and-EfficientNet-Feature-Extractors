# Domain Adaptation with VGG-19 and EfficientNet

This repository contains experiments on **Unsupervised Domain Adaptation (UDA)** and **Pretraining** using **VGG-19** and **EfficientNet-B0** as feature extractors. The workflows include Exploratory Data Analysis (EDA), model training, and evaluation with ADDA and DANN frameworks.  

---

## 📂 Repository Structure

### Jupyter Notebooks
- **Exploratory Data Analysis.ipynb**  
  Exploratory Data Analysis (EDA) on the Source and Target datasets for Pretraining and UDA.

- **Pretraining and UDA with VGG-19 (ADDA, DANN).ipynb**  
  Pretraining on Source with **VGG-19** and UDA on Target using **ADDA** and **DANN** feature extractors.

- **UDA with EfficientNet.ipynb**  
  Pretraining on Source with **EfficientNet-B0** and UDA on Target using **ADDA** and **DANN** feature extractors.

---

## 📦 Google Drive Repository  

All datasets, preprocessed data, codes, results, and analysis are stored in Google Drive:  
🔗 [Google Drive Repository](https://drive.google.com/drive/folders/1RpE_2ZpH4cppfzb-S6_ayxotNJQpT7B3?usp=sharing)

### Folder Breakdown
- **Datasets**  
  Contains the **original datasets** for both source and target.

- **Preprocessed Datasets**  
  Includes **channel and size converted** versions of the datasets (ready for model input).

- **Codes**  
  Scripts and notebooks executed in **Google Colab (L4 GPU)** for EDA and model training (mirrored here in GitHub).

- **Results**  
  Contains result files including:
  - Excel sheets
  - Confusion matrices
  - Best-5 UDA checkpoints (`.pth` files)

- **Analysis on Results**  
  Excel-based analysis of outcomes (graphs, filtering, averaging, etc.) for both pretraining and UDA.
