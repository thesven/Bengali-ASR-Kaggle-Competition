---
dataset_info:
  features:
  - name: input_features
    sequence:
      sequence: float32
  - name: labels
    sequence: int64
  splits:
  - name: valid
    num_bytes: 961354832
    num_examples: 1000
  - name: train
    num_bytes: 9612070048
    num_examples: 10000
  download_size: 1670316522
  dataset_size: 10573424880
---
# Dataset Card for "bengali-ai-train-set-tiny"



# Dataset Description

- **Homepage:** [OOD-Speech: A Large Bengali Speech Recognition Dataset for Out-of-Distribution Benchmarking](https://arxiv.org/abs/2305.09688)
- **Paper:** [OOD-Speech: A Large Bengali Speech Recognition Dataset for Out-of-Distribution Benchmarking](https://arxiv.org/abs/2305.09688)

### Whisper Model Information

- **Model Homepage:** [openai/whisper-tiny on Hugging Face](https://huggingface.co/openai/whisper-tiny)
- **Model Paper:** [Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)

## Dataset Summary

This dataset is designed to help finetune the `openai/whisper-tiny` model with additional information in the Bengali language. It consists of an additional 11,000 labeled audio samples from the OOD-Speech dataset, specifically designed for out-of-distribution benchmarking in Bengali.

## Supported Tasks and Leaderboards

The primary task supported by this dataset is automatic speech recognition (ASR) in the Bengali language, specifically for finetuning the `openai/whisper-tiny` model.

## Languages

The dataset is in Bengali.

## Dataset Structure

### Data Instances

Each instance in the dataset consists of an audio sample in Bengali along with its corresponding transcription.

### Data Fields

- `audio`: The audio sample in Bengali.
- `transcription`: The corresponding transcription of the audio sample in Bengali.

### Data Splits

The dataset is split into training and validation sets. The training set consists of 10,000 samples, and the validation set consists of 1,000 samples.

## Additional Information

### Dataset Curators

The dataset has been curated by "thesven".

### Licensing Information

Licensing information for the OOD-Speech dataset can be found in the original paper.

### Citation Information

    @article{OOD-Speech2023, title={OOD-Speech: A Large Bengali Speech Recognition Dataset for Out-of-Distribution Benchmarking}, author={Authors of the OOD-Speech paper}, journal={arXiv preprint arXiv:2305.09688}, year={2023} }