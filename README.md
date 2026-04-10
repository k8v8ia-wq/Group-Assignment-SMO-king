# Fake News Detection Using DistilBERT 📰🤖

This repository contains the code, dataset, and report for our group project on **Fake News Detection** using Deep Learning. We utilized the Hugging Face `transformers` library to fine-tune a pre-trained **DistilBERT** model for highly accurate binary text classification.

## 📌 Project Overview
In the era of social media, the rapid spread of fake news poses a significant threat. This project aims to build an automated, high-precision detection system. Instead of training a model from scratch, we leverage **Knowledge Distillation** via `DistilBERT`, which retains 97% of BERT's language understanding while reducing the parameter count by 40%.

* **Model:** `distilbert-base-uncased`
* **Task:** Binary Text Classification (Real: `0`, Fake: `1`)
* **Accuracy Achieved:** >99%

## 📂 Repository Structure
```text
📦 Group-Assignment-Fake-News
 ┣ 📂 data
 ┃ ┗ 📜 fakenews.csv                 # The raw dataset (Ensure this is downloaded)
 ┣ 📜 525_group_assignment.ipynb     # Main Jupyter Notebook containing all training/evaluation code
 ┣ 📜 Report.pdf                     # Final Project Report
 ┗ 📜 README.md                      # Project documentation

