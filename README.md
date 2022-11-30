# Starbucks-Capstone-Challenge

## Table of Contents

1. [Installation](https://github.com/kirstencampbellyoung/Data-science-blog-post/blob/main/README.md#installation)
2. [Project Motivation](https://github.com/kirstencampbellyoung/Data-science-blog-post/blob/main/README.md#project-motivation)
3. [File descriptions](https://github.com/kirstencampbellyoung/Data-science-blog-post/blob/main/README.md#file-descriptions)
4. [Results](https://github.com/kirstencampbellyoung/Data-science-blog-post/blob/main/README.md#results)

# Installation 

I have used the Anaconda distribution of Python. In addition to the default libraries I also installed 
- .
- .
- .

# Project Motivation

This project forms part of the final project in Udacity's data science Nanodegree course. Starbucks has provided some simulated data from a series of offers they are promoting to their customers on their rewards mobile app. The aim of this project is to identify which groups of people are most responsive to each type of offer, and how best to present each type of offer.

# File descriptions

I have the 3 datasets I used -
1. **portfolio.json:** rewards program users (17000 users x 5 fields)
-  gender: (categorical) M, F, O, or null
-  age: (numeric) missing value encoded as 118
-  id: (string/hash)
-  became_member_on: (date) format YYYYMMDD
-  income: (numeric)

2.  **profile.json:** Offers sent during 30-day test period (10 offers x 6 fields)
- reward: (numeric) money awarded for the amount spent
- channels: (list) web, email, mobile, social
- difficulty: (numeric) money required to be spent to receive reward
- duration: (numeric) time for offer to be open, in day
- offer_type: (string) bogo, discount, informational
- id: (string/hash)

3. **transcript.json:** Event log (306648 events x 4 fields)
- person: (string/hash)
- event: (string) offer received, offer viewed, transaction, offer completed
- value: (dictionary) different values depending on event type
    * offer id: (string/hash) not associated with any "transaction"
    * amount: (numeric) money spent in "transaction"
    * reward: (numeric) money gained from "offer completed"
- time: (numeric) hours after start of test

There a jupyter notebook 'Starbuck_Capstone_notebook.ipynb' to showcase the work and analysis performed to address the problem statement above.

# Results

The findings of my analysis can be found in this [blog post](https://medium.com/@kirstencyoung/so-youre-thinking-of-listing-your-property-on-airbnb-aa542beede47)

