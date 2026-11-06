# Biomedical NLP: Named Entity Recognition

## 1. Project Overview

This project focuses on Biomedical Natural Language Processing (NLP), with a particular emphasis on Named Entity Recognition (NER).

The main objective is to identify and classify biomedical entities in scientific and clinical texts using different deep learning and Transformer-based architectures.

Several models are implemented, trained, and evaluated to compare their performance on biomedical text data.

## 2. Project Objectives

The main objectives of this project are:

- Explore Natural Language Processing techniques for biomedical text.
- Implement deep learning architectures for Named Entity Recognition.
- Fine-tune pre-trained biomedical language models.
- Compare classical neural networks with Transformer-based models.
- Evaluate model performance using standard NER metrics.

## 3. Dataset

The project uses the **BC5CDR dataset** in IOB format.

The dataset is divided into three subsets:

- `train.tsv`: Training data.
- `devel.tsv`: Development and validation data.
- `test.tsv`: Testing data.

## 4. Models Implemented

The following architectures are explored:

### 4.1. Deep Learning Models

- **BiLSTM**
- **BiLSTM-CRF**

### 4.2. Transformer-Based Models

- **BioBERT**
- **ClinicalBERT**
- **PubMedBERT**

## 5. Evaluation

The models are evaluated using standard Named Entity Recognition (NER) metrics:

- **Precision**
- **Recall**
- **F1-score**

A comparison of the different architectures is provided through the experimental results.

## 6. Trained Models

The trained models are hosted on [Hugging Face](https://huggingface.co/).

Visit the [`models/`](models/README.md) directory to access the model repositories and download the trained models.

## 7. Notebooks

The `notebooks/` directory contains the Jupyter notebooks used for:

- Model implementation.
- Data preprocessing.
- Model training.
- Model evaluation.
- Experimental analysis.



### 8. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Biomedical-NLP
```

## 9. Author

**Oumaima Brahmia**

Biomedical NLP Project
