# intent-classification-nlp-transformers
This project demonstrates multilingual **intent classification**, **named entity recognition (NER)**, and **topic modeling** using modern NLP techniques with pre-trained Transformer models. The system is deployed using **Gradio** for real-time user interaction.

---

## Features

### 1.Intent Classification
- **Model**: [`qanastek/XLMRoberta-Alexa-Intents-Classification`](https://huggingface.co/qanastek/XLMRoberta-Alexa-Intents-Classification)
- **Tool**: HuggingFace `TextClassificationPipeline`
- **Deployment**: Gradio web interface
- **Use Case**: Understand user intent in chatbots and virtual assistants

### 2.Named Entity Recognition (NER)
- **Model**: `dslim/bert-base-NER`
- **Purpose**: Extract names, organizations, and locations from user input
- **Deployment**: Gradio interface

### 3.Topic Modeling with BERTopic
- **Dataset**: `tokyo_2020_tweets.csv` (10,000 tweets about Tokyo 2020 Olympics)
- **Model**: `BERTopic`
- **Insights**: Visualizations of dominant topics from tweet data

---

## Dataset

- **Source**: Tweets dataset loaded from local Google Drive path
- **File**: `tokyo_2020_tweets.csv`
- **Content**: 10,000 textual tweets related to the Tokyo 2020 Olympics

---

## Tech Stack

- Python 
- HuggingFace Transformers 
- Gradio 
- BERTopic 
- Pandas 
- Google Colab 

---

##  Setup Instructions

pip install transformers gradio bertopic pandas

