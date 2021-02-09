# Name of Project

ML_CA02_eMail Spam Classifers using Naive Bayes


# Project Overview

In this exercise we train the model with set of emails labelled as either from Spam or Not Spam. 
There are 702 emails equally divided into spam and non spam category.
And then we test the model on 260 emails. 
Next, the model will predict the category of these emails and compare the accuracy with correct classification that we already know in the step above


# Files

1. train-mails: https://drive.google.com/drive/folders/15Mf5IwlxX0GbQ7SzntZ3BBjNExmcM972?usp=sharing
2. test-mails: https://drive.google.com/drive/folders/16MbqFedqFEH6zr4HFkWV8HQmEcgU1Ib6?usp=sharing


# Packages

```bash
import os
import numpy as np
from collections import Counter
from sklearn.naive_bayes import GaussianNB
from sklearn.metrics import accuracy_score
from google.colab import drive
```


# Installation

- Please download test and train two dataset from the google drive above or from the zip files.
- Upload files or just copy the path to the colab
- import all the needed packages
- Mounted the google drive to make files readable: drive.mount('/content/drive/')
- Enjoy the code


# Contact info

Name: Mandy He
Email: she3@lion.lmu.edu
