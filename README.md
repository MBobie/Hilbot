# Hilbot: A Data-Centric Framework for Financial Intent Classification

## Overview
This repository contains the dataset and implementation supporting the paper:

**"When Simpler Models Win: A Data-Centric Evaluation of Financial Intent Classification under Low-Resource Conditions."**

The project introduces **Hilbot**, a dual-input hybrid framework that combines:
- **TF-IDF (lexical features)** for discriminative precision
- **GloVe embeddings + CNN** for semantic representation

The study evaluates classical, neural, and hybrid models under **low-resource and imbalanced conditions**, demonstrating that **simpler models can outperform complex architectures when data is limited**.

---

## Dataset

The dataset consists of **1,386 samples across 33 financial intent classes**, constructed from heterogeneous sources:

- **JSON data (`data.json`)**  
  Conversational financial queries representing real-world user intents  

- **CSV data (`HilData.csv`)**  
  Structured financial records converted into natural language queries  

### Key Characteristics
- Highly **imbalanced class distribution**
- Combination of **structured and unstructured data**
- Designed to simulate **real-world financial NLP conditions**

---

## Repository Structure
