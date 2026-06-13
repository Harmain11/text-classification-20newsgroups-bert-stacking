# Text Classification on 20 Newsgroups with BERT and Stacking

## Overview  
This notebook demonstrates fine-tuning a pretrained BERT model using Keras-BERT to classify the 20 Newsgroups text dataset. It includes data preprocessing, tokenization, model construction, training, evaluation, and visualization of results. An ensemble stacking approach with deep learning and traditional ML techniques is also outlined.

## Features  
- Download and preprocess 20 Newsgroups dataset  
- Use pretrained BERT from Google for feature extraction  
- Implement tokenization aligned with BERT vocabulary  
- Construct a classification model with BERT layers and custom softmax output  
- Train model using TensorFlow and Keras with GPU acceleration  
- Evaluate with accuracy, classification report, and confusion matrix visualization  
- Prepare for stacking ensemble techniques  

## Tech Stack  
- Python  
- Jupyter Notebook / Google Colab  
- TensorFlow and Keras  
- keras-bert library  
- scikit-learn  
- pandas, numpy, matplotlib, seaborn  
- TensorFlow Addons (AdamW optimizer)  

## How to Use  
1. Clone or download the repository.  
2. Open `20newsgroups-bert-stacking-classification.ipynb` in Jupyter or Google Colab.  
3. Run all cells sequentially to install dependencies, download data, train and evaluate the model.  
4. Modify parameters such as batch size, sequence length, and epochs as desired for experimentation.  

## Status  
This notebook is organized and prepared for clean presentation and reproducibility on GitHub.