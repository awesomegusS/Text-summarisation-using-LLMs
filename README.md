# dsci-6004-final-project-godswill-sumanth
Text Summarisation using Pre-trained Large Language Models

# Project: Text Summarisation using Pre-trained Large Language Models

## Overview:
Text summarisation using pre-trained large language models like Pegasus and BART is explored in this project. The objective was to fine-tune these models on two different datasets, SAMSum and SciTLDR, for abstractive text summarisation, and evaluate their performance using the ROUGE metric.
Pegasus and BART, both transformer-based models, were fine-tuned on the datasets. The SAMSum dataset consists of human-annotated dialogues, while SciTLDR contains scientific documents paired with concise summaries. The models were trained for one epoch, and their performance was evaluated using ROUGE scores.
Results show that both Pegasus and BART performed well, with varying degrees of success depending on the dataset. On SAMSum, both models achieved similar results, while on SciTLDR, BART outperformed Pegasus. Further experimentation and longer training epochs could potentially improve the performance of these models.

## Aim
The aim of this project is to explore the effectiveness of pre-trained large language models, specifically Pegasus and BART architectures, for text summarisation tasks. The project focuses on fine-tuning these models on two different datasets, SAMSum and SciTLDR, and evaluating their performance using the ROUGE metric. By conducting this research, we aim to assess the suitability of these models for generating high-quality summaries in specific domains and contribute to the broader understanding of text summarisation techniques in natural language processing.


## Dataset:
The SAMSUM and SCiTLDR datasets are downloaded from hugging face.

## Usage:
The notebook file contains all the experiments performed and you can run the code to download the models from hugging face, load and preprocess the dataset, and fine tune the models to obtain the ROUGE scores.

