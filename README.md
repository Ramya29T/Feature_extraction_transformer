# Feature Extraction Transformer

This project uses an encoder-only Transformer (BERT) to extract the attention weights of each feature in a dataset. The model processes tabular data and analyzes feature importance using attention scores.

## Features

- Utilizes a pre-trained BERT model for feature importance extraction.
- Processes tabular data by treating each feature as a separate token.
- Extracts attention weights to evaluate feature contributions.

## Installation

Ensure you have Python installed, then install the required dependencies:

```bash
pip install torch torchvision torchaudio
pip install transformers
pip install pandas scikit-learn
