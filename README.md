# Temporal Sentiment Analysis

This repository contains implementation of generative model used in *Yumo Xu and Shay B. Cohen. 2018.* [Stock Movement Prediction from Tweets and Historical Prices](https://aclanthology.org/P18-1183.pdf). The model is applied to the [ParlVote dataset](https://aclanthology.org/2020.lrec-1.624/) \([download_link](https://data.mendeley.com/datasets/czjfwgs9tm/2)\) .

## Problem Statement
Given a sequence of texts (t1,…tn-1,tn) with binary labels (l1,…ln-1,ln), where label l_i corresponds to text t_i. Use the generative model in  which takes input text (t1,…t_n-1,t_n), labels (l_1…l_n-1) and predicts label l_n. 

