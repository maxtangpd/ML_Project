## ML PROJECT

>  Music Genre classification using Logistic Regression, KNN，SVM，CNN

### Overview
To compare the result across multiple architectures, we have took two approaches for this problem: One using the classic approach of extracting features and then using a classifier. The second approach, wich is implemented on the src file here is a Deep Learning approach feeding a CNN with a melspectrogram.

Requirement：
librosa
matplotlib
lightgbm
tensorflow
wheel

### Results
Here are the current results on the test set:

| Model | Acc |
|-------|-----|
| Logistic Regression | 0.653 |
| KNN | 0.687 |
| SVM | 0.724 |

For the deep learning approach we have the result. 

| Model | Acc |
|-------|-----|
| CNN | 0.832 |

### Dataset

Download the GTZAN dataset (http://marsyas.info/downloads/datasets.html)
The dataset contains 30-second audio files including 10 different genres including reggae, classical, country, jazz, metal, pop, disco, hiphop, rock and blues.Once you downloaded the dataset, unzip and move the dataset to your home folder. After you have done this, you should have the following content in the data folder.


### How to run
Just run the .ipynb in the code folder.




