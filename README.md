## ML PROJECT

>  Music Genre classification using KNN，SVM，CNN

### Overview


### Results

To compare the result across multiple architectures, we have took two approaches for this problem: One using the classic approach of extracting features and then using a classifier. The second approach, wich is implemented on the src file here is a Deep Learning approach feeding a CNN with a melspectrogram.

You can check in the nbs folder on how we extracted the features, but here are the current results on the test set:

| Model | Acc |
|-------|-----|
| Decision Tree | 0.5160 |
| Random Forest | 0.6760 |
| ElasticNet | 0.6880 |
| Logistic Regression | 0.7640 |
| SVM (RBF) | 0.7880 |

For the deep learning approach we have tested a simple custom architecture. 

| Model | Acc |
|-------|-----|
| **CNN 2D** | **0.832** |

### Dataset

And how to get the dataset?

1. Download the GTZAN dataset (http://marsyas.info/downloads/datasets.html)


### How to run




