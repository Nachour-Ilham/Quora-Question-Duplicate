# Questions Similarity with Siamese Neural Networks
# Objective

The goal of this project is to build a system using Siamese Neural Networks to learn and determine the similarity between questions. With the rise of platforms such as Quora and Stack Overflow, the task of question retrieval has gained significant attention. It is crucial for users to check if a similar question has already been asked and answered by the community.

# Data 
The data to be used for training and testing is Quora Question Pairs Dataset. This dataset can be downloaded from this link:
http://qim.fs.quoracdn.net/quora_duplicate_questions.tsv


# Description
The architecture of the system is described in the paper cited in the reference, and its schema is depicted in figure 1. The system will be tested only for English, even if the paper is also concerned with Arabic.

![image](https://github.com/Nachour-Ilham/Quora-Question-Duplicate/assets/112636125/b240e5ec-4de5-481e-beff-5d5d4ffd637c) 
  
  Figure 1: General architecture of the MaLSTM model


# Reference
[Manhattan Siamese LSTM for Question Retrieval in Community Question Answering](https://hal.science/hal-02271338/file/Manhattan_Siamese_LSTM_for_Question_Retrieval_in_Community_Question_Answering__1_.pdf)https://hal.science/hal-02271338/file/Manhattan_Siamese_LSTM_for_Question_Retrieval_in_Community_Question_Answering__1_.pdf
