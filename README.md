# XARM: Explainable Review Mining Approach

This repository contains datasets and code for conducting experiments on review mining with a focus on explainable AI techniques. The work explores preprocessing, sampling methods, and deep learning models for extracting insights from textual review data.

## Directory Structure

### Data Files
- **Amazone_Dataset.csv**: Contains review data for experiments.
- **requirment_annotatted_dataset.csv**: Annotated dataset used in various models.

### Code Files

#### Preprocessing and Sampling
- **`Oversampling_and_Under_samplimpling_sarcasm_countvatrizer (2).ipynb`**: Demonstrates cleaning text data and balancing datasets using oversampling/undersampling techniques with CountVectorizer.
- **`Oversampling_and_Under_samplimpling_sarcasm_tfiddf_multiclassification.ipynb`**: Similar to the above but utilizes TF-IDF for text representation.

#### Model Training
- **`BIGRU Model.ipynb`**: Implements the Bidirectional GRU model for review classification.
- **`CNN Modell.ipynb`**: Uses Convolutional Neural Networks for review mining.
- **`GRU Model.ipynb`**: Employs a GRU-based architecture for text classification.
- **`LSTM, BILSTM_models.ipynb`**: Explores LSTM and BiLSTM models for review classification.
- **`RNN_MODEL.ipynb`**: Implements the RNN model for review classification.
- **`ROC BILSTM_OVER_UNDER_SAMPLING.ipynb`**: Focuses on evaluating the BiLSTM model's performance with balanced datasets.

### Documentation Files
- **`README.md`**: General overview of the repository.
- **`CNN LIME.pdf`**: Analysis of CNN model using LIME (Local Interpretable Model-agnostic Explanations).
- **`CNN_SHAP_KAGGLE.pdf`**: SHAP (SHapley Additive exPlanations) analysis applied to CNN on Kaggle review data.
- **`MLP_LIME.pdf`**: Analysis of the MLP model using LIME.

## Requirements
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `pandas`, `numpy`, `scikit-learn`, `keras`, `tensorflow`

## Running the Experiments

### Preprocessing
1. Start with one of the preprocessing notebooks:
   - **`Oversampling_and_Under_samplimpling_sarcasm_countvatrizer (2).ipynb`**
   - **`Oversampling_and_Under_samplimpling_sarcasm_tfiddf_multiclassification.ipynb`**
2. Review text cleaning and dataset balancing approaches.

### Model Training
1. Choose a notebook based on the desired model:
   - **`GRU Model.ipynb`**
   - **`BIGRU Model.ipynb`**
   - **`CNN Modell.ipynb`**
   - **`LSTM, BILSTM_models.ipynb`**
   - **`RNN_MODEL.ipynb`**
2. Run the selected notebook and follow the prompts to train the model.
3. (Optional) Use evaluation notebooks like **`ROC BILSTM_OVER_UNDER_SAMPLING.ipynb`** to analyze model performance.

### Evaluation
- Use the associated PDF reports for insights on model interpretability using LIME and SHAP.
