# Reproducing Roberts et al. 2020

This repository contains code to reproduce the results of Roberts et al. (2020) "How Much Knowledge Can you Pack
Into the Parameters of a Language Model?". Using the HuggingFace transformers library, we reproduced the results for
`t5-small`, `t5-base`, and `t5-large` models for the WebQuestions dataset.

## Dependencies
Python 3.7 was used, but Python 3.5+ should work. Packages required include PyTorch, the HuggingFace transformers
and datasets libraries, and `tqdm`. All dependencies are listed in `requirements.txt`.

## Code
The main experiment code is in the notebook `t5-webqa.ipynb`, including data downloading, preprocessing, training,
and evaluation. For additional experiments see the `additional` folder.

## Downloading Data
Thanks to the HuggingFace datasets library, the downloading of data is done programmatically in the notebook and
does not have to be separately performed. The downloaded dataset is cached.

