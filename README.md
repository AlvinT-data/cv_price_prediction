# Multimodal Product Price Prediction

This project builds a multimodal machine learning system to predict retail product prices by combining visual, structured, and LLM-extracted features.

The model integrates ResNet-50 image embeddings with engineered numeric features such as quantity and unit information. Additional semantic attributes are extracted using Google AI Studio to enrich structured representations.

Using log-price regression and SMAPE for evaluation, the multimodal model achieves a 20% reduction in SMAPE compared to a constant-mean baseline, demonstrating the value of feature fusion across modalities.

This repository includes data preprocessing pipelines, feature engineering steps, model architecture implementation, training scripts, and evaluation code.

📊 Presentation slides: [https://www.canva.com/design/DAHBFgeQOPY/ahpGFKs6FSoyus-UczfkIg/edit?utm_content=DAHBFgeQOPY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton]
