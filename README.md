# ML
KNN Classifier for MAGIC Gamma Telescope
Overview
This project implements a K-Nearest Neighbors (KNN) classifier to distinguish gamma (signal) from hadron (background) events in the MAGIC Gamma Telescope dataset. Built in Python using scikit-learn, it includes data preprocessing, model training, and evaluation. This is part of my machine learning learning journey.
Dataset

Source: MAGIC Gamma Telescope dataset (UCI, donated by P. Savicky).
Features: 10 numerical features (e.g., fLength, fWidth, fSize).
Target: Binary class (1: Gamma, 0: Hadron).
Preprocessing: Standardized features, oversampled training data.

Dataset included as magic04.data.
Installation

Clone the repo:git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Set up a Python environment (3.8+):python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate


Install dependencies:pip install -r requirements.txt

requirements.txt:numpy
pandas
scikit-learn
matplotlib
imbalanced-learn
jupyter


Run Jupyter:jupyter notebook



Or use Google Colab to open KNN_MAGIC_Gamma.ipynb.
Usage

Open KNN_MAGIC_Gamma.ipynb in Jupyter or Colab.
Run cells to:
Load and preprocess data.
Split into train (60%), validation (20%), test (20%).
Train KNN (n_neighbors=3).
Evaluate with classification report.


Modify n_neighbors or splits to experiment.

Results
The KNN model achieves ~80% accuracy (update with your classification_report output). Gamma class has higher recall. Histograms visualize feature distributions.
Contributing
Fork, branch, commit, and submit a pull request. Follow PEP 8 and add comments.
License
MIT License
Contact

GitHub: aadarsh2812
Email: your-kasaadarsh@gmail.com

