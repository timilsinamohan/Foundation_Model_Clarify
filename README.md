# Project Overview

This is lung cancer relapse project for early stage lung cancer patient. This repository contains eight Jupyter notebooks, each demonstrating different foundation models sourced from the Hugging Face library. Please note that due to GDPR compliance, we are unable to provide the datasets used within these notebooks. However, we have provided the synthetic dataset using Synthetic Data Vault Python Library (https://docs.sdv.dev/sdv). The Mahalanobis Distance between Real and Synthetic Data: 0.6626. The Mahalanobis distance is a measure of the distance between two distributions (in this case, the real and synthetic datasets) that takes into account correlations between the variables. The smaller the value, the closer the synthetic data is to the real data's distribution.

## Dependencies

The project requires the following Python packages. Ensure you have these versions installed by referring to the list below:

accelerate==0.27.2
huggingface-hub==0.21.3
scikit-learn==1.4.1.post1
scikit-multilearn==0.2.0
scipy==1.12.0
seaborn==0.13.2
sentencepiece==0.2.0
sentry-sdk==1.41.0
torch==2.2.1
tqdm==4.66.2
transformers==4.38.2
sdv ==1.2.0


## Running the Notebooks

To explore the machine learning models implemented in this repository, please use the corresponding notebook files as outlined below:

- **Classical Classifiers**: For classical ML approaches, run `lung_cancer_fourteen_classical_classifier_aim.ipynb`.
- **GPT-2 Fine-tuning**: Explore fine-tuning GPT-2 with `gpt_finetuned.ipynb`.
- **GPT-Neo Fine-tuning**: For experiments with GPT-Neo, use `gpt_neo_finetune.ipynb`.
- **BERT Models**: To utilize BERT models, open and run `bert.ipynb`.
- **Falcon**: Examine Falcon model integrations in `falcon.ipynb`.
- **LLaMA**: For the LLaMA model, proceed with `llama.ipynb`.
- **Mistral**: Explore the Mistral model using `mistral.ipynb`.
- **Zero-shot Learning**: For zero-shot learning models, use `zero_shot.ipynb`.

## Important Notes

**Ensure that your Python environment is properly set up with all required packages before running the notebooks.**
