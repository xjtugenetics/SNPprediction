#Functional disease-associated SNPs prediction (FDSP)

#Introduction

We developed functional disease-associated SNPs prediction (FDSP), a toolkit for predicting disease risk SNPs. Our tools includes two parts: pre-processing pipeline and FDSP package in R.

Several scripts consist of pre-processing pipeline. These pipeline perform calculating linkage disequilibrium(LD) and minor allele frequency(MAF), creating positive dataset and negative dataset according to lead SNPs of diseases, and annotating SNPs with epigenetics elements.

FDSP package includes three sections: training set and test set creation, training prediction model with machine learning algorithm, and disease-associated SNPs prediction.

#Author

FDSP is written by Chen Yi-xiao, Yao shi and Dong shan-shan from Genetics and Bioinformatics Lab, Xi An Jiao Tong Univ, Sch Life Sci & Technol, Minist Educ, Key Lab Biomed Informat Engn, Xian 710049, Peoples R China.


#License

This software is distributed under the terms of GPL 3.0

#Source

https://github.com/xjtugenetics/SNPprediction

#Contact

You can contact yangtielin@mail.xjtu.edu.cn when you have any questions, suggestions, comments, etc. Please describe with more details, and attach your command line and log messages if possible.

#Requirements

awk, R (>= 3.3.2), PLINK, bedtools

R packages: caret, methods, randomForest, doParallel, parallel

#Preparation
##Setup folder framework

```
tar -zxvf  FDSP.tar.gz
cd /path/pre-prosessing
ls
data  ld  prep  scripts
```
