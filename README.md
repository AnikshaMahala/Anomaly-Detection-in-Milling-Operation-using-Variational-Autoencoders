# Anomaly-Detection-in-Milling-Operation-using-Variational-Autoencoders

This repository contains the implementation and results for exploring, modeling, and analyzing milling data using a Variational Autoencoder (VAE) for anomaly detection. The project is organized into three Jupyter notebooks, each focusing on a specific stage of the workflow.

## Project Structure

### 1. **`1_EDA_milling_data.ipynb`**
- **Purpose**: Perform exploratory data analysis (EDA) on the milling dataset.
- **Key Features**:
  - Data preprocessing and cleaning.
  - Visualization of important features and trends.
  - Initial insights into the dataset's structure and potential anomalies.

### 2. **`2_building_VAE.ipynb`**
- **Purpose**: Build and train a Variational Autoencoder (VAE) for feature representation and anomaly detection.
- **Key Features**:
  - Implementation of the VAE architecture.
  - Training the model on the preprocessed data.
  - Validation and evaluation of the model's performance.

### 3. **`3_anomaly_results.ipynb`**
- **Purpose**: Analyze the results of the VAE and detect anomalies in the milling data.
- **Key Features**:
  - Reconstruction error analysis.
  - Threshold determination for anomaly detection.
  - Visualization of detected anomalies and their characteristics.

## Requirements

To run the notebooks, ensure you have the following dependencies installed:

- Python 3.8+
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow or PyTorch (depending on the VAE implementation)

## Results

The results highlight the capability of the VAE to:
- Represent complex patterns in the milling data.
- Identify anomalous behaviors with high reconstruction error.
- Provide interpretable visualizations for anomaly analysis.


