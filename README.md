# BWIN

This repository provides the complete code and resources for a machine learning project dedicated to financial analysis and portfolio management. It encompasses data preparation, robust LSTM model training, comprehensive portfolio evaluation, and in-depth model interpretability.

## Repository Structure

*   **[hyperparameters/](hyperparameters/)**: This directory stores configuration files that define the hyperparameters used for training the machine learning models.
*   **[inputs_data/](inputs_data/)**: This folder contains all raw and processed input data. It includes a Jupyter notebook for data preparation and the final processed dataset used for model training.
*   **[model_training/](model_training/)**: This folder houses the Jupyter notebook used for training the machine learning models. It also includes a comparison file detailing model performance metrics.
*   **[portfolio_results/](portfolio_results/)**: This folder stores the outcomes of portfolio analysis and evaluation. It includes a text file with analysis results and a Jupyter notebook for portfolio evaluation.
*   **[saved_models/](saved_models/)**: This directory is dedicated to storing all trained machine learning models and preprocessed data in `.npz` and `.keras` format.
*   **[SHap_graphs/](SHap_graphs/)**: This folder stores SHAP (SHapley Additive exPlanations) graphs, which are crucial for interpreting the predictions of the machine learning models.
*   **[standard_scalars/](standard_scalars/)**: This directory contains all saved standard scaler objects used for normalizing or standardizing data during the preprocessing phase.