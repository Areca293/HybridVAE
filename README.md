# Intrusion Detection Project

This project is a Jupyter notebook for intrusion detection using machine learning with PyTorch.

Repository: [GitHub - BlackCrowxyz/hybrid-vae](https://github.com/BlackCrowxyz/hybrid-vae)

## Prerequisites

- Python 3.x
- Jupyter Notebook

## Installation

Install the required packages:

```bash
pip install torch torchvision scikit-learn pandas numpy matplotlib seaborn tqdm imbalanced-learn
```

## Dataset

To run the project, download the following dataset files from the [CIC-IDS-2017 Dataset page](http://cicresearch.ca/CICDataset/CIC-IDS-2017/):

- MachineLearningCSV.zip
- GeneratedLabelledFlows.zip

Fill out the download form with any random information (name, email, etc.) to access the download links. Extract both .zip files into the project directory. The notebook will use the extracted CSV files for training and testing.

## Running the Project

1. Open the notebook: `jupyter notebook intrusiondetection.ipynb`
2. Run all cells in order.

## Report

For detailed information about the project, refer to the [HybridVAE Report](HybridVAE-Report.pdf).