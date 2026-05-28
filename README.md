# News Topic Classifier using HuggingFace Transformers

A transformer-based NLP application that classifies news articles into multiple categories using zero-shot classification with HuggingFace Transformers.

The system predicts the most relevant category for a given article based on semantic understanding rather than keyword matching.

## Features

* Multi-category news classification
* Zero-shot transformer inference
* Dynamic label-based prediction
* Confidence score generation
* Interactive command-line style interface
* Multiple predefined testing examples

## Categories Supported

* Sports
* Politics
* Technology
* Business
* Health
* Finance
* Education
* Entertainment

## Technologies Used

* Python
* HuggingFace Transformers

## Model Used

`MoritzLaurer/mDeBERTa-v3-base-mnli-xnli`

## Why This Model Was Used

This project uses a zero-shot classification model instead of a traditional fine-tuned classifier.

The selected model was chosen because it:

* supports dynamic category prediction,
* performs strong semantic reasoning,
* does not require custom training,
* works effectively for flexible NLP classification tasks.

Unlike traditional classifiers that require retraining for new categories, this model can classify text using custom labels provided at runtime.

## Concepts Demonstrated

* Transformer Inference
* Zero-Shot Classification
* Semantic Text Understanding
* Multi-Class NLP Classification
* Confidence-Based Prediction
* Dynamic Label Matching

## Example Output

```python
Enter news article text (or type 'exit'): The football team won the championship after a thrilling final match.
Predicted Category: sports
Confidence Score: 93.42%
```

## Installation

```bash
pip install transformers
```

## Run the Project

Open the notebook in Google Colab or Jupyter Notebook and run the cells sequentially.

## Project Purpose

This project was built to gain practical experience with:

* HuggingFace transformer pipelines,
* zero-shot NLP systems,
* semantic text classification,
* modern transformer-based inference workflows.
