# DS5500_PCG_Classification
The link to the 2016 Physionet challenge - https://physionet.org/content/challenge-2016/1.0.0/
The segmentation_auto.zip -> contains the intervals of the segments/states for each audio file.This is a .mat file. For eg: 
  {"S1": 0,599 ,
    "Systole" : 600,1000 ,
    "S2" : 10001,1200,
    "diastole": 1201,1300,
    "S1" :...... } 
 The samples from 0 - 599 correspond to S1. From 600 to 1000, the sample fall under Systole.
 
 The training data has been divided into 5 folders. Each folder contains reference.csv file, which gives us the labels( Normal or Abnormal) 
 for each of the audio file.
 
 Other papers for reference:
 1. https://www.sciencedirect.com/science/article/pii/S2212017316303164
 2. https://www.springerprofessional.de/en/the-implementation-of-pretrained-alexnet-on-pcg-classification/17020308
 3. https://arxiv.org/pdf/1806.06506.pdf
 
 
