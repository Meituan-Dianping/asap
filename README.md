# ASAP-NAACL2021
[TOC]

## General Introduction

This repository contains the data of the [NAACL 2021](https://2021.naacl.org/)  paper: [ASAP: A Chinese Review Dataset Towards Aspect Category Sentiment Analysis and Rating](https://arxiv.org/abs/2103.06605)

**ASAP** is a large-scale Chinese restaurant review dataset for Aspect category Sentiment Analysis (ACSA) and review rating Prediction (RP).

ASAP includes 46, 730 genuine user reviews from the [Dianping](https://www.dianping.com/) App, a leading Online-to-Offline (O2O) e-commerce platform. Besides a 5-star scale rating, each review is manually annotated according to its sentiment polarities towards 18 pre-defined aspect categories, including food, service, enrionment and so on. We split the dataset into a training set (37,300), a validation set (4,940) and a test set (4,940) randomly.  

## Data Example

![image](https://github.com/Meituan-Dianping/asap/blob/master/example_review.png)

## Read File

  ```
  import pandas as pd
  
  data = pd.read_csv(file_path, header=0)
  ```
## Data Label

The sentiment polarity over the aspect category is labeled as 1(Positive), 0(Neutral), −1(Negative), −2(Not-Mentioned)

The star rating ranges from 1 to 5.

## Citation

Please cite the following paper if you found it useful in your work.

```
@inproceedings{bu2021asap,
    title={{ASAP}: A Chinese Review Dataset Towards Aspect Category Sentiment Analysis and Rating Prediction},
    author={Bu, Jiahao and Ren, Lei and Zheng, Shuang and Yang, Yang and Wang, Jingang and Zhang, Fuzheng and Wu, Wei},
    booktitle={NAACL-HLT},
    year={2021}
    } 
```

## Contact

Jiahao Bu: bujh1994@gmail.com

Lei Ren: renlei04@meituan.com

Jingang Wang: wangjingang02@meituan.com

