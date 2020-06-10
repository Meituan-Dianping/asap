# ASAP
### General Introduction

This repository contains the data of the paper "ASAP: A Chinese Review Dataset Towards Aspect Category Sentiment Analysis and Rating Prediction".

**ASAP** is a large-scale Chinese restaurant review dataset for Aspect category Sentiment Analysis (ACSA) and review rating Prediction (RP).

ASAP includes $47, 300$ genuine user reviews from the [Dianping](https://www.dianping.com/) App, a leading Online-to-Offline (O2O) e-commerce platform. Besides a $5$-star scale rating, each review is manually annotated according to its sentiment polarities towards $18$ pre-defined aspect categories, including food, service, enrionment and so on. We split the dataset into a training set ($37,300$), a validation set ($5,000$) and a test set ($5,000$) randomly.  

We hope the release of the dataset could shed some light on the fields of sentiment analysis.

### Data Example

![image](https://github.com/Meituan-Dianping/asap/blob/master/example_review.pdf)

### Read file

  ```
  import pandas as pd
  
  data = pd.read_csv(file_path, header=0)
  ```
### Data labels

The sentiment polarity over the aspect category is labeled as 1(Positive), 0(Neutral), −1(Negative), −2(Not-Mentioned)

The star rating ranges from 1 to 5.
