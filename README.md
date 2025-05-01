# Indian Sign Language Recognition using Prototypical Networks 👐

[![Python 3.11+](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-ee4c2c.svg)](https://pytorch.org/get-started/locally/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A state-of-the-art few-shot learning solution for Indian Sign Language (ISL) recognition that achieves **99.6% accuracy** with only 15 samples per class. Bridges communication gaps for 63M+ hearing-impaired Indians through AI-powered gesture recognition.

## Key Features ✨

- 🖐️ **5-Shot Learning**: Recognizes new signs with just 5-15 examples using Prototypical Networks
- 🖼️ **Advanced Preprocessing**: Hybrid edge detection combining adaptive thresholding + Otsu's method
- 📊 **Multi-Model Comparison**: Benchmarks against CNN (99.98%), LSTM (98.19%), and Attention-CNN (99.67%)
- 🔄 **Cross-Dataset Validation**: Tested on two distinct ISL datasets from Kaggle


## Datasets 📦

### 1. ISL Alphabet & Digits (35 classes)
https://www.kaggle.com/datasets/vaishnaviasonawane/indian-sign-language-dataset


### 2. ISL Words & Numbers (50 classes)
https://www.kaggle.com/datasets/princegupta0353/indian-sign-language-image-dataset

## Models

1. CNN
2. CNN- with Attention
3. LSTM
4. SVM
5. Few-Shot Models
  1.  Prototypical Network
  2.  Matching Network 

## Results
### Deep learning and Machine Learning models
|Model                 | Accuracy | Training Data Required |
|----------------------|----------|------------------------|
| CNN                  | 99.98%   | 960 images/class       | 
| LSTM                 | 98.19%   | 960 images/class       | 
| Attention-CNN        | 99.67%   | 960 images/class       | 
| SVM                  | 99.90%   | 960 images/class       |

### Few Shot Models
|Model                 | Model Configuration       | Accuracy | Training Data Required |
|----------------------|---------------------------|----------|------------------------|
| Prototypical Network | 5-Way 5-Shot (Dataset 1)  | 99.60%   | 15 images/class        |
| Prototypical Network | 5-Way 1-Shot (Dataset 1)  | 98.80%   | 11 images/class        |
| Prototypical Network | 5-Way 5-Shot (Dataset 2)  | 95.72%   | 15 images/class        |
| Prototypical Network | 5-Way 1-Shot (Dataset 2)  | 87.48%   | 11 images/class        |
| Matching Network     | 5-Way 5-Shot (Dataset 1)  | 97.7 %   | 15 images/class        |
