# 🕊️ PolyHope at IberLEF 2025: Optimism, Expectation or Sarcasm?

Hope Speech Detection in Social Media Texts

Welcome to the repository for the PolyHope Shared Task at IberLEF 2025! This repository contains the implementation and resources developed for tackling the challenge of detecting and classifying hope in social media texts across English and Spanish, including differentiating genuine hope from sarcasm.

## 🌟 Task Overview
The PolyHope shared task focuses on analyzing the nuanced expression of hope in social media, acknowledging its complexity when intertwined with expectation, optimism, or sarcasm. It aims to promote research in inclusive language technologies, enhance understanding from psychological perspectives, and develop computational models for fine-grained detection of hope across languages.

## 🔍 Subtasks
The challenge is divided into two main subtasks:

Subtask 1: Binary Hope Speech Detection

Subtask 1.a: English

Subtask 1.b: Spanish

👉 Classify texts into:

Hope: Tweets expressing hope, expectation, or desire.

Not Hope: Tweets without hopeful sentiment.

Subtask 2: Multiclass Hope Speech Detection

Subtask 2.a: English

Subtask 2.b: Spanish

👉 Classify texts into:

Generalized Hope: Broad, non-specific hope.

Realistic Hope: Hope grounded in plausible outcomes.

Unrealistic Hope: Hope for highly unlikely outcomes.

Not Hope: No hope expressed.

Sarcasm: Sarcastic use of hopeful language.

## 📂 Repository Contents
This repository includes:

Folder / File	Description
- data_cleaning/	Scripts for cleaning and preprocessing raw tweet data.
- data_augmentation/	Code for augmenting the dataset to address class imbalance.
- few_shot_samples/	Scripts for extracting few-shot samples for low-resource settings.
- roberta_binary_classification/	Code for fine-tuning and predicting binary labels with XLM-RoBERTa model.
- roberta_multiclass_classification/	Code for fine-tuning and predicting multiclass labels with XLM-RoBERTa model.
- data_analysis/	Scripts for class distribution and exploratory data analysis.
- README.md	This readme file.
  
## ✅ If you require access to the dataset, please visit the official competition page:
👉 https://www.codabench.org/competitions/5509/

Note: The dataset is provided by the PolyHope shared task organizers and may require registration or agreement to specific terms of use.
