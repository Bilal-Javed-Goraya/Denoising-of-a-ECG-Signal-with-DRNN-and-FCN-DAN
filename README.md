# Denoising ECG Signal with DRNN and FCN-DAE

## Overview

This GitHub repository contains the implementation of denoising Electrocardiogram (ECG) signals using Deep Recurrent Neural Network (DRNN) and Fully Convolutional Network with Denoising Autoencoder (FCN-DAE). The project leverages state-of-the-art numerical methods and deep learning techniques to enhance the accuracy and robustness of ECG signal denoising.

## Project Structure

- **`data/`**: Contains the dataset used for training and testing.
- **`Training/`**: Includes the implementation of DRNN and FCN-DAE models.
- **`Training/`**: Utility functions for data processing, metrics calculation, and visualization.
- **`Training/`**: Jupyter notebooks for experimentation and analysis.
- **`results/`**: Saved test results for DRNN and FCN-DAE models.
- **`requirements.txt`**: List of dependencies for easy environment setup.

## Setup

1. Clone the repository:

```bash
git clone https://github.com/Bilal-Javed-Goraya/Denoising of a ECG Signal with  DRNN and FCN-DAN.git
cd Denoising of a ECG Signal with  DRNN and FCN-DAN
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run experiments:

   - Execute `DeepLearningMethodsNotebook.ipynb` to train the DRNN model.
   - Execute `DeepLearningMethodsNotebook.ipynb` to train the FCN-DAE model.
   - Evaluate models using `DeepLearningMethodsNotebook.ipynb`.

4. Explore results:

   - View denoising results in the `results/` directory.
   - Analyze model performance in the `Training/` directory.

## Numerical Methods Utilized

The project employs the following numerical methods:

- **Gradient Descent Optimization**: Utilized for updating weights during model training.
- **Linear Regression for Weights**: Applied to adjust model parameters.
- **Backpropagation**: Key method for calculating gradients during model training.
- **Mean Squared Error Loss Function**: Used to quantify differences between predicted and true signals.
- **Cross-Validation**: Ensures robust model evaluation and performance generalization.
- **Random Sampling**: Employed for diverse evaluation scenarios and visualizations.

## Report

For a detailed report on the project, refer to `Report_Denoising_ECG_with_DRNN_and_FCN_DAE.pdf`.

Feel free to explore, experiment, and contribute to the project for continuous improvement in denoising ECG signals.

## Acknowledgments

Special thanks to the open-source community and contributors for their valuable libraries and tools used in this project.
