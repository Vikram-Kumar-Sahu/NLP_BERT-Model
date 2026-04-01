# 📘 NLP Assignment: Sentiment Classification with BERT & Tokenization Strategies

## 📌 Overview
This project implements a **sentiment classification pipeline** using a pretrained **BERT (Bidirectional Encoder Representations from Transformers)** model.

The main objective is to:
- Classify sentences into **positive or negative sentiment**
- Compare two tokenization strategies:
  - **WordPiece (baseline)**
  - **Byte Pair Encoding (BPE)**

---

## 🚀 Features
- End-to-end NLP pipeline using **PyTorch**
- Custom dataset handling with `Dataset` and `DataLoader`
- Fine-tuning pretrained **bert-base-uncased**
- Implementation of:
  - WordPiece tokenizer (from HuggingFace)
  - Custom-trained BPE tokenizer
- Evaluation using:
  - Accuracy
  - F1 Score

---

## 📂 Dataset
The project uses the **SST-2 (Stanford Sentiment Treebank)** dataset, which contains labeled sentences for sentiment analysis.

### Structure:
- `train.csv`
- `val.csv`
- `test.csv`

Each file contains:
- `sentence` → input text  
- `label` → sentiment (0 = negative, 1 = positive)

---

## ⚙️ Installation

Install required dependencies:

```bash
pip install transformers datasets tokenizers sentencepiece torch scikit-learn
