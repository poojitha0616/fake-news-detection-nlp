**Fake News Detection using NLP and Deep Learning**
**Overview**

This project implements a Natural Language Processing (NLP) based fake news detection system using both traditional deep learning and transformer-based models.

The objective is to classify news articles as Real or Fake by comparing the performance of LSTM networks with advanced transformer architectures such as BERT and RoBERTa.

**Models Implemented**

LSTM (Long Short-Term Memory)

BERT (Bidirectional Encoder Representations from Transformers)

RoBERTa (Robustly Optimized BERT)

**Technologies Used**

Python

TensorFlow / Keras

HuggingFace Transformers

Scikit-learn

Pandas

NumPy

**Project Structure**
Fake-News-Detection/
│
├── NLP.ipynb
├── NLP.docx
├── Fake_News_Detection_Presentation.pptx
├── lstm_model.keras
├── config.json
├── merges.txt
├── special_tokens_map.json

**Methodology**

Data preprocessing and cleaning

Text tokenization

Model training (LSTM and Transformer models)

Model evaluation and comparison

Performance metrics analysis (Accuracy, Precision, Recall, F1-score)

**Results**

The transformer-based models (BERT and RoBERTa) achieved higher classification accuracy compared to the traditional LSTM model, demonstrating the effectiveness of contextual embeddings for fake news detection.

Future Enhancements

Deploy the model as a web application

Integrate real-time news API for live detection

Improve model explainability using attention visualization

Expand dataset for better generalization

**Author**

Poojitha Reddy Vontela
Master’s Student – Computer Science
Texas A&M University – Corpus Christi
