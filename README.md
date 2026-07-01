# Seeds Dataset Classification using SVM

This project implements a Support Vector Machine (SVM) to classify wheat seed varieties based on geometric features such as area, perimeter, compactness, length, and width.

## Dataset
The project uses the "Seeds Dataset," which contains physical parameters of kernels from three different varieties of wheat.

## Features
*   **Preprocessing:** Cleaning the dataset by removing unnecessary columns and handling null values.
*   **Modeling:** Using `scikit-learn` to implement an SVM classifier with a linear kernel.
*   **Evaluation:** Calculating model accuracy to assess performance.

## Prerequisites
To run this project, you will need:
*   Python 3.x
*   pandas
*   numpy
*   scikit-learn
*   gradio (used for potential interface deployment)

## Installation
Clone this repository and install the required libraries:
```bash
pip install pandas numpy scikit-learn gradio
