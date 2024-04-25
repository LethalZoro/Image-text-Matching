# Image text Matching
## Overview:
This project delves into the task of image-text matching (ITM). The aim is to investigate the effectiveness of various machine learning models and algorithms in addressing these tasks and to offer insights into their real-world applicability.


## Introduction:
The study explores the efficacy of machine learning and deep learning algorithms in two significant applications: image-text matching and game learning. Various neural network architectures are employed to tackle these tasks, and a comparative analysis is conducted based on task-specific performance metrics. State-of-the-art architectures are discussed, and their results are analyzed.

### Image-Text Matching:
For the image-text matching task, the objective is to predict whether an image and a textual description correspond to each other, treated as a binary classification problem. Different binary classifiers are trained and evaluated on a dataset comprising image-text pairs. Performance is compared using metrics such as accuracy, recall, F1-score, and BCA. Additionally, preprocessing techniques are explored to enhance model performance.
#### The models used for the image-text matching task are:
 1. CNN-based Model:
 1. VGG16-based Model:
 1. MobileNet-based Model:


####  Results:
The results are after training each model for mearly 20 epochs on the Flickr8k dataset. The models are evaluated on the test set, and the performance metrics are calculated. The results are summarized in Table 1.

### Table 1: Comparative Analysis of Performance Metrics:
| Model             | Accuracy | Recall | F1-Score | BCA  |
|-------------------|----------|--------|----------|------|
| CNN-based Model  | 65.7%      | 64.3%  |   73.9%    | 67.1%  |
| VGG16-based Model| 64.9%      | 62.4%  |   72.9%    |  67.5% |
| MobileNet-based Model| 67.5% |   66.8%  |    75.6%  |  68.1% |

