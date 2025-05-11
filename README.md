# 🏡 Real Estate Price Estimation using LLaMA 3.2 + LoRA + Unsloth

This project fine-tunes a **LLaMA 3.2 1B** model using **LoRA (Low-Rank Adaptation)** via **Unsloth**, enabling it to predict house prices from structured property listings. The model is trained on a large dataset and served using **vLLM** for fast inference.

---

## 🏠 Overview

This project aims to transform a large structured real estate dataset into instruction-style prompts suitable for fine-tuning LLMs. The model learns to predict house prices by analyzing features like number of bedrooms, bathrooms, lot size, location, previous sale date, and more.

### 🔍 Key Features

- Converts tabular data into LLM-readable prompts
- Fine-tunes LLaMA 3.2 with LoRA adapters for efficiency

---

## 📊 Dataset

- Format: `.jsonl` structured property listings (e.g., price, bed, bath, size, zip code)
- Size: ~800K sold listings used for training
- Original data: [USA Real Estate Dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset)

