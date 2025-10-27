## Product Price Prediction using BERT with Regressor Head
📘 Overview

To predicts the market price of products based on their text descriptions and images. The goal is to develop a model capable of understanding both textual and visual product attributes to estimate a realistic market value.

🧠 Model

A BERT-based model with a regression head was trained on the product dataset.

Text Input: Product descriptions

Image Input: Product images

Output: Predicted market price

The model was fine-tuned for regression tasks using Smooth Mean Absolute Percentage Error (SMAPE) as the evaluation metric.

Evaluation Metric

The SMAPE (Symmetric Mean Absolute Percentage Error) is calculated as:
SMAPE = (1/n) * Σ |predicted_price - actual_price| / ((|actual_price| + |predicted_price|)/2)


A lower SMAPE indicates better model performance.

📊 Results

Model: BERT + Regression Head

Evaluation Metric: SMAPE

Achieved Accuracy: ~50 SMAPE

🗂️ Dataset

The dataset contains:

Product Descriptions: Textual data describing the product

Product Images: Visual representation of the product

Target Variable: Actual market price
