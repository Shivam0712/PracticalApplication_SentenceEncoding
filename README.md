# PracticalApplication_SentenceEncoding

Sentence Encoding helps to represent any sentence as a numerical vector, thus, making it possible to use mathematical operations on it.

![Image description](https://github.com/Shivam0712/PracticalApplication_SentenceEncoding/blob/master/Images/SentEnc.PNG)

The notable applications of sentence encoding are:
1. Text Classification (Sentiment Analysis).
2. Text Similarity Measurements. (Use of BERT in Google Search Engine).

But beyond, sentiment analysis and use in giant Search Engines, Sentence encoding hold immense potential to impact/increase the efficiency of business processes in medium and small size companies, specifically startups.

In this project, I have demonstrated a prototype that uses sentence encoding to develop a system for 'Automatic Job Description Filler'.

## Problem Description:

1. An Indian platform collects 'Job Descriptions' from employers, process it, and post it on website. One of the most time consuming and labor-intensive task in this process is to clean and process these job descriptions written by employers.

2. Currently, this process is done manually, where 6 to 8 people spend 8 hours a day. They clean these inputs, break them into sentences, finding similar sentences from previous published JD's, and finally compile it to make the publishable job description.

![Image description](https://github.com/Shivam0712/PracticalApplication_SentenceEncoding/blob/master/Images/IOJD.PNG)

3. We will design a system which cleans the input, forms sentences, and uses sentence encoding to extract similar sentences from past JD's.

## Data Description

We have 2 datasets for solving this problem:

1. **Corpus:** Previous published Job Descriptions without the information of employers input. We need to extarct similar sentence from this corpus. **(Size: 400k JD's)**

![Image description](https://github.com/Shivam0712/PracticalApplication_SentenceEncoding/blob/master/Images/corpus.PNG)

2. **Input-Output Pair** Previous published Job Descriptions with the information of employers input. We will use this to build and validate our system. **(Size: 40k Pairs)**

![Image description](https://github.com/Shivam0712/PracticalApplication_SentenceEncoding/blob/master/Images/Pair.PNG)

## Suggested System Design
