# Evaluating Embedding Representations for Multiclass Code Smell Detection: A Comparative Study of CodeBERT and General-Purpose Embeddings

This repository contains the notebook and data files used to support the experimental results reported in the associated scientific article. Its purpose is to provide the materials required to reproduce the comparative analysis conducted on code smell classification using **OpenAI embeddings** and **CodeBERT embeddings**.

## Repository contents

The repository should contain the following files:

- `main.ipynb`
- `dataset_smells_embeddings_openai.pkl`
- `dataset_smells_embeddings_codebert.pkl`
- `README.md`

## Execution environment

The notebook was developed in **Google Colab**. It may also be executed in a local Jupyter environment, provided that the required dependencies are installed and the data files are placed in the expected location.

## Requirements

Recommended Python version: **3.10** or higher.

Install the required packages with:

```bash
pip install pandas numpy matplotlib scikit-learn transformers jupyter
