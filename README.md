# BWIN

This repository contains the code and resources for a machine learning project focused on financial analysis and portfolio management. The project involves data preparation, model training (specifically LSTM models), portfolio evaluation, and model interpretability.

## Repository Structure

*   **[hyperparameters/](hyperparameters/)**: This directory stores configuration files, such as [`model_hyperparameters.json`](hyperparameters/model_hyperparameters.json), which define the hyperparameters used for training the machine learning models.
*   **[inputs_data/](inputs_data/)**: Contains raw and processed input data. It includes a Jupyter notebook for data preparation ([`data_preper.ipynb`](inputs_data/data_preper.ipynb)) and the final processed dataset ([`final_data.csv`](inputs_data/final_data.csv)) used for model training.
*   **[model_training/](model_training/)**: Houses the Jupyter notebook ([`machine_learning_model.ipynb`](model_training/machine_learning_model.ipynb)) used for training the machine learning models. It also includes a comparison file ([`comparison.csv`](model_training/comparison.csv)) likely detailing model performance metrics.
*   **[portfolio_results/](portfolio_results/)**: Stores the outcomes of portfolio analysis and evaluation. This includes a text file with analysis results ([`portfolio_analysis.txt`](portfolio_results/portfolio_analysis.txt)) and a Jupyter notebook for portfolio evaluation ([`portfolio_evaluate.ipynb`](portfolio_results/portfolio_evaluate.ipynb)).
*   **[saved_models/](saved_models/)**: This directory is dedicated to storing trained machine learning models (e.g., [`best_lstm_model.keras`](saved_models/best_lstm_model.keras), [`best_lstm_model_filtered.keras`](saved_models/best_lstm_model_filtered.keras)) and preprocessed data in `.npz` format (e.g., [`lstm_preprocessed_data.npz`](saved_models/lstm_preprocessed_data.npz)).
*   **[SHap_graphs/](SHap_graphs/)**: Intended to store SHAP (SHapley Additive exPlanations) graphs, which are used for interpreting the predictions of the machine learning models.
*   **[standard_scalars/](standard_scalars/)**: This directory likely contains saved standard scaler objects used for normalizing or standardizing data during the preprocessing phase.