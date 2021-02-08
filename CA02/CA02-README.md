## Introduction to Machine Learning
### Computer Assignments 
#### Should you have questions or issues accessing any documents please contact me via email at jamie.meugniot@lmu.edu or via Teams. 
_________________________________________________________________________________________________________________________________________________________________________________

### CA02 Assignment - Spam Email Detection using Naive Bayes

In this assignment, we will train the model with a set of emails labelled as either SPAM or NOT SPAM. There are 702 emails divided evenly into SPAM and NOT SPAM. Using 260 emails we will test the model to predict the category of the emails and compare the accuracy with the correct classification that we already know. 

The assignment includes 2 data files: 
1. train-mails - 442 files
2. test-mails - 260 files

Packages to import: 
- import os 
- import numpy as np
- from collections import Counter
- from sklearn.naive_bayes import GaussianNB
- from sklearn.metrics import accuracy_score

**Downloading & Accessing the Data**

Download data and save in your desired google colab folder. **Note the path to these folders as you will need it when reading the data in later**

In order to access the data you have just saved to your google colab folder you need to add the following code before running the program. If you do not import the drive you will get an error saying that the file could not be found given the path you gave. 

    from google.colab import drive
    drive.mount('/content/drive')

When reading in your data files from your selected google colab folder when downloaded please make adjustments to the file path as needed to access your selected folder. My folder paths are as follows: 

    TRAIN_DIR = "/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA02/Data/train-mails"
    TEST_DIR = "/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA02/Data/test-mails"

**Code Comments**

Code comments will always be before the code they are describing or in line with the code they are referencing. 
