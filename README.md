# CIFAR-10 Classification Project

This repository contains the code for training and evaluating a deep learning model on the CIFAR-10 dataset. The project demonstrates the steps involved in downloading the dataset, pre-processing the data, building the model, training it, and evaluating its performance.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images. 

You can download the dataset using the Kaggle API:

```bash
kaggle competitions download -c cifar-10
```
## Results

After training, the model achieved an accuracy of **30.18%** on the CIFAR-10 test dataset. 

### Matrix

```plaintext
Unique classes in true labels: [0 1 2 3 4 5 6 7 8 9]
Unique classes in predictions: [0 1 2 3 4 5 6 7 8 9]
              precision    recall  f1-score   support

    airplane       0.39      0.37      0.38      2000
  automobile       0.58      0.31      0.40      2000
        bird       0.14      0.59      0.22      2000
         cat       0.28      0.17      0.21      2000
        deer       0.42      0.20      0.27      2000
         dog       0.41      0.16      0.23      2000
        frog       0.49      0.27      0.35      2000
       horse       0.54      0.28      0.37      2000
        ship       0.33      0.39      0.36      2000
       truck       0.53      0.28      0.37      2000

    accuracy                           0.30     20000
   macro avg       0.41      0.30      0.32     20000
weighted avg       0.41      0.30      0.32     20000

Precision: 0.4098
Recall: 0.3018
Accuracy: 0.3018
