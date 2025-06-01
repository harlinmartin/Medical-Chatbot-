# Medical-Chatbot-LLamA
# 🦙 LLaMA 3.2 1B - Model Download & Setup (Windows)

This repository contains the code and setup to download and use the [meta-llama/Llama-3.2-1B](https://huggingface.co/meta-llama/Llama-3.2-1B) model from Hugging Face.

## 📦 Folder Structure

llama/
├── llama3_env/ # Python virtual environment
├── models/
│ ├── Llama-3.2-1B/ # Model folder
│ └── download_llama.py # Script to download model
└── README.md # This file


## ✅ Prerequisites

- Python 3.9+
- Hugging Face account and token
- `huggingface_hub` Python package

## 🚀 How to Use

1. Create virtual environment  
2. Install `huggingface_hub`  
3. Authenticate using your Hugging Face token  
4. Run the download script

## 📚 Dataset 

The training dataset was collected from multiple open-source datasets on [Kaggle](https://www.kaggle.com). It contains approximately **280,000** medical question–answer pairs in `.csv` and `.json` formats.

### 📦 Datasets Used:

- [AI Medical Chatbot (Kaggle)](https://www.kaggle.com/datasets/shivamb/medical-chatbot)
- [Medical Chatbot Dataset (Kaggle)](https://www.kaggle.com/datasets/tamojit/medical-chatbot)
- [Dataset for medical related chatbots (Kaggle)](https://www.kaggle.com/datasets/jessemostipak/medical-chatbot-intent-classification)
- [Medical Chatbot](https://www.kaggle.com/datasets/bulentsiyah/medical-chatbot)

> ⚠️ **Note:** These datasets need preprocessing to match the input format required for fine-tuning the `meta-llama/Llama-3.2-1B` model (e.g., converting to JSONL with `prompt` and `response` keys).

