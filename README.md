# GenAI-HuggingFace

This repository contains examples of using Generative AI models via the Hugging Face ecosystem. It includes several Jupyter notebooks demonstrating various natural language processing (NLP) tasks using different state-of-the-art models.

## Project Overview

The project provides hands-on demonstrations of how to integrate and use Hugging Face models for tasks such as sentiment analysis, question answering, and text generation. It utilizes the `transformers` and `langchain` libraries to interact with these models.

## Notebooks Included

### 1. `HuggingFacePipeline.ipynb`
This notebook demonstrates how to use the Hugging Face `pipeline` API for quick and easy inference.
- **Task:** Sentiment Analysis
- **Model Used:** `distilbert-base-uncased-finetuned-sst-2-english` (DistilBERT)
- **Description:** It shows how to initialize a sentiment analysis pipeline and run predictions on sample texts to classify them as POSITIVE or NEGATIVE, along with their confidence scores.

### 2. `currency_flan_t5_large.ipynb`
This notebook explores the integration of Hugging Face models with LangChain for querying.
- **Task:** Question Answering
- **Model Used:** `google/flan-t5-large` (FLAN-T5)
- **Description:** It uses LangChain's `HuggingFaceHub` wrapper to connect to the Hugging Face API and query the FLAN-T5 model. For example, it asks the model "What is the currency of India?" and retrieves the answer.

### 3. `llama2.ipynb`
This notebook focuses on text generation using the Llama 2 model.
- **Task:** Text Generation (Chatbot/Recommendations)
- **Model Used:** `meta-llama/Llama-2-7b-chat-hf` (LLaMA 2 7B Chat)
- **Description:** It sets up the Hugging Face pipeline for text generation using the Llama 2 model. It demonstrates how to authenticate, load the model using `AutoTokenizer` and `pipeline`, and prompt the model for show recommendations based on user preferences.
