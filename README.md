# Fashionability-Prediction

## Inspiration
Based on the use of the Fashion 144K dataset in the papers: Joint Ranking and Classification using Weak Data for Feature Extraction(http://www.f.waseda.jp/hfs/SimoSerraCVPR2016.pdf) and 
An Analysis of Human-centered Geolocation(https://arxiv.org/abs/1707.02905).

## What it does
Predicts the Fashionability score (1-10) of images based on the Fashion 144k Dataset. 

## How I built it
I used Resnet50 for Feature extraction process connecting to a 10-d fc layer. The model was trained on a subset of the dataset, that is, 3000 train mages and 1000 validation images. 

## Accomplishments that I'm proud of
After training longer, my accuracy came out to be around 14% compared to 17% in the original paper. Hyperparameters optimized using Hyperas.
