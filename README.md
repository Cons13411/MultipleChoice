# MultipleChoice
This repository contains the code for fill in multiple-choice question answering
# IMPORTANT NOTICE

Unfortunately, I cannot share the dataset for this code. However, its general structure is as follow:

  The dataset for this task, for each instance, contains a passage (it could be any kind of passage, a normal text, or a code) in which only one word is replaced with a BLANK identifier. Each instance also contains 4 to 6 choices (single words). The task is to find the best possible choice among these provided options to
  be replaced in the passage instead of the BLANK spot.

#  Architecture 

The code also had some parts for analyzing the data and also some preparation that I removed those parts.

The proposed method can use any contextualized language model which can process two separated sentences at once, e.g., BERT, RoBERTa, XLNet .... .
In this code, I only used RoBERTa and XLMRoBERTa.  

The general architecture is like this :

![Alt text](archi.png?raw=true "Title")

The further analysis such as model comparison and prediction bias analysis will be added here....
