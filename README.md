# Classifier Comparison Tool

## Overview

The Classifier Comparison Tool is a Streamlit-based application that allows users to compare different machine learning classifiers on various datasets. Users can choose between datasets and classifiers, adjust classifier parameters, and visualize model performance and results.

## Features

- **Dataset Selection**: Choose from Iris, Breast Cancer, or Wine datasets.
- **Classifier Options**: Compare K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Random Forest classifiers.
- **Parameter Configuration**: Adjust classifier parameters through interactive sliders.
- **Model Evaluation**: Display accuracy and detailed classification reports.
- **Visualization**: View PCA-reduced 2D scatter plots of the dataset.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/classifier-comparison-tool.git
   cd classifier-comparison-tool

## Install the required packages:
   ```bash
   pip install -r requirements.txt
```

## Run the Streamlit app:
   ```bash
   streamlit run app.py
```

## Usage
- Open the Streamlit app in your browser by following the URL provided in your terminal.
- Select a dataset and classifier from the sidebar.
- Configure the classifier parameters using the provided sliders.
- Click on "Run" to train the model and visualize the results.
- Review the accuracy, classification report, and PCA visualization on the main page.
