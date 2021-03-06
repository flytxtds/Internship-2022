## Data Science Internship Opportunities at Flytxt R&D (May-July 2022)
We are looking for self-motivated individuals with a passion to solve real-world problems in emerging areas of machine learning/AI including federated privacy preserving machine learning and explainable AI. You will be responsible to design, code, test and deploy PoCs which demonstrate the value in applying these advanced techniques on usecases in customer experience management. You would be working in a fast-paced environment, and would need to pick up concepts through a combination of self-learning and your assigned mentor's guidance. Please note that this will be a remote internship program.

## Who can apply?
1. Students in 3rd/4th year B.Tech program in Computer Science or a related discipline (Applied Mathematics, Statistics, Electrical and/or Computer Engineering) with a focus on Artificial Intelligence / Machine Learning. Final year M.Tech/MS/Ph.D students from the above disciplines are also eligible.
2. Should be passionate about advanced machine learning/AI.
3. Should be able to devote a minimum of 2 months, starting May 2022

## Problem Description
This year, we have two problems from which you can choose **one**


#### Problem 1: Privacy preserving federated learning on tabular data
Create a federated privacy preserving model to predict if a bank customer will subscribe to a term-deposit or not by securely combining customer & marketing data which is split across two banks, without requiring data sharing in plain. Both banks have the same set of customer KPIs, but non-overlapping customers (horizontal federated learning).

The model should be built using Federated Secure XGBoost, an open-source project from UC Berkeley RISE Lab (https://github.com/mc2-project/secure-xgboost)

#### Success Criteria:
Federated privacy-preserving model should have higher F1 score than a standard XGBoost model trained on either party's local data alone. Brownie points for setting up an interactive demo of the model on public cloud, covering the following functionality:

1. Upload of encrypted datasets.
2. Secure learning of the model.
3. Inference on encrypted data; decryption of results at client end.

#### Dataset:

https://archive.ics.uci.edu/ml/datasets/bank+marketing (41188 instances, 20 features). Horizontal federated learning is simulated by splitting the dataset horizontally into two at random

---
#### Problem 2: Explainable AI based on causal reasoning
Create an explainable causal model for customer churn which:
1. Automatically visualizes the causal structure in the observed data.
2. Predicts if a user will churn, along with top-3 causal factors based on the model's belief (as an explanation).

The model should be built using CausalNex, an open-source project from McKinsey (https://github.com/quantumblacklabs/causalnex)
#### Success Criteria:
1. Prediction accuracy of the causal model should be comparable to that of a baseline model based on Random Forest.
2. Domain expert's validation of the learned causal structure; subjective evaluation of causes for churn on a random subset of cases

Brownie points for setting up an interactive demo of the model on public cloud, covering the following functionality:
1. User uploads a churn dataset
2. Gets a causal structure visualization which he/she can edit.
3. KPIs for a user can be entered to get a prediction along with an explanation based on top-3 causal factors  

#### Dataset:
https://www.kaggle.com/jpacse/datasets-for-churn-telecom (71047 instances, 58 features)  

## Application Process
1. Interested candidates should choose <ins>**one**</ins> problem from the above list of problems and prepare a <ins>**1 page**</ins> proposal describing their approach and key milestones. Please note that the proposal should clearly state how <ins>**you**</ins> would approach the problem and the <ins>**corresponding work breakdown structure along with a timeline.**</ins> **Proposals exceeding 1 page and/or which are very generic will not be considered.**
2. You can submit your proposal, latest resume and other relevant details using this form till **April 8th 2022**: [Apply Now](https://forms.gle/E3S7ruQJzNRgYatD6)
3. Shortlisted candidates will be notified by **April 15th, 2022**, followed by an online interview.
4. Selected candidates will be notified by **April 29th, 2022**; Internship would start from **1st week of May 2022.**

## Perks
1. Work experience in cutting edge areas of machine learning/AI on real-world customer experience management problems
2. Stipend

## Queries
You can submit your queries [here](https://forms.gle/hUcoBxyXzFfkhc4H7). We will get in touch with you.

