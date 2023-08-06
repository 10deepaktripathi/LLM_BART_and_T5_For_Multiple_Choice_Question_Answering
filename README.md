# Description



Your challenge in this task is to answer multiple-choice questions written by an LLM. While the specifics of the process used to generate these questions aren't public, we've included 200 sample questions with answers to show the format, and to give a general sense of the kind of questions in the test set. However, there may be a distributional shift between the sample questions and the test set, so solutions that generalize to a broad set of questions are likely to perform better. Each question consists of a prompt (the question), 5 options labeled A, B, C, D, and E, and the correct answer labeled answer (this holds the label of the most correct answer, as defined by the generating LLM).

This competition uses a hidden test. When your submitted notebook is scored, the actual test data (including a sample submission) will be made available to your notebook. The test set has the same format as the provided test.csv but has ~4000 questions that may be different is subject matter.


## Directory Structure
- [bart-and-flan-t5-base-model.ipynbb](./bart-and-flan-t5-base-model.ipynb):Notebook contains detailed steps taken for modelling the tweets related to disater data
- [train.csv](./train.csv): the training set, which includes the labeled tweets.
- [test.csv](./test.csv): the test set; your task is to predict the tweets available in test file

