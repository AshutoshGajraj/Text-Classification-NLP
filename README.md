# 20 Newsgroups Text Classifier

A PyTorch project that classifies 20 Newsgroups articles by category using text preprocessing and an LSTM classifier.

## Notebooks

- `notebooks/nlp_classification_w_pytorch.ipynb` — uses the mini 20 Newsgroups subset (100 articles from each newsgroup).
- `notebooks/nlp_classification_w_pytorch_all_data.ipynb` — uses the full 20 Newsgroups dataset.

## Run

```bash
uv sync
uv pip install torch
cd notebooks
jupyter lab
```

Run Jupyter from `notebooks/` because the notebooks use relative dataset and model paths.

## Project

- `data/20_newsgroups/` — full dataset
- `notebooks/model_nlp_classification_all_data.pt` — saved full-dataset model
- `pyproject.toml` — Python dependencies

## Data source

The [20 Newsgroups dataset](http://kdd.ics.uci.edu/databases/20newsgroups/20newsgroups.html) is from the UCI KDD Archive.

