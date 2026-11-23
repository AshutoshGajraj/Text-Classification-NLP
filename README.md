# 20 Newsgroups Text Classifier

A PyTorch notebook that classifies 20 Newsgroups articles by category. It loads the dataset, cleans and encodes the text, trains an LSTM classifier, and visualizes predictions.

## Run

```bash
uv sync
cd notebooks
jupyter lab
```

Open `nlp_classification_w_pytorch.ipynb` and run it from top to bottom. Run Jupyter from `notebooks/` because the notebook uses relative dataset and model paths.

## Project

- `notebooks/nlp_classification_w_pytorch.ipynb` — data preparation, training, and evaluation
- `data/mini_newsgroups/` — sample dataset
- `notebooks/model_nlp_classification.pt` — saved trained model
- `pyproject.toml` — Python dependencies

PyTorch is also required:

```bash
uv pip install torch
```
