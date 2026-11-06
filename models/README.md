# Trained Models

This directory provides access to the trained models developed for the Biomedical Named Entity Recognition (NER) project.

The models are hosted on [Hugging Face](https://huggingface.co/) to facilitate access and downloading without storing large model files directly in this GitHub repository.

## Available Models

| Model | Description | Hugging Face |
|---|---|---|
| BiLSTM Classic | A classical BiLSTM model for biomedical named entity recognition. | [View Model](https://huggingface.co/Oumaimabrh023/BiLSTM_Classique) |
| BiLSTM-CRF | A BiLSTM model combined with a CRF layer for sequence labeling. | [View Model](https://huggingface.co/Oumaimabrh023/bilstm_crf_model) |
| BioBERT | A biomedical language model fine-tuned for NER. | [View Model](https://huggingface.co/Oumaimabrh023/ner_biobert_model) |
| ClinicalBERT | A clinical language model fine-tuned for NER. | [View Model](https://huggingface.co/Oumaimabrh023/clinicalbert_model) |
| PubMedBERT | A biomedical language model fine-tuned for NER. | [View Model](https://huggingface.co/Oumaimabrh023/pubmedbert_ner_model) |

## Downloading the Models

To download a model, visit its corresponding Hugging Face repository and follow the instructions provided on its model page.

## Usage

The trained models can be used for biomedical named entity recognition and evaluated on biomedical text datasets.

Please refer to the `notebooks/` directory for the training, evaluation, and prediction workflows.

## Notes

- Model files are hosted externally on Hugging Face.
- This GitHub repository contains the source code, notebooks, documentation, and experimental results.
- Please refer to the corresponding model cards for model-specific details and requirements.
