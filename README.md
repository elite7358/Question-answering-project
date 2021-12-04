# The instructions:
To run Pytorch lightning module, the pytorch -lightning module needs to be installed on jupyter notebook using line command - 
!pip install pytorch-lightning

Authors: Ankit Anand, Zi-Min Weng

## Purpose: 
  We build up a Question anwsering model to predict the answer of questions from BioASQ and SQuAD 2.0 datasets. 
## Get start:
  Open and run the Question Answering.ipynb to see all the results.
## Introduction:
  The model is implemented in huggingface transformer and pytorch. The T5ForConditionalGeneration and DistilBertForQuestionAnswering are used in Question Answering.ipynb and SQUAD.ipynb respectively.
  The code of Question Answering.ipynb is developed under nlp2021 environment on Cheaha, includes the training and validation part of T5 model.
  
The code of SQUAD.ipynb is developed first under Google Colab then transplate to the DeepNLP environment on Cheaha.
The code present the training and validate part of question answering model of DistilBert on SQuAD 2.0 dataset.
We use huggingface transformers packages and Pytorch to train our model.

## Datasets:
- SQuAD 2.0(`squad/train-v2.0.json`, `squad/dev-v2.0.json`)
- BioASQ (`BioASQ/BioASQ-train-factoid-4b.json`,`BioASQ-train-factoid-5b.json` , `BioASQ-trian-factoid-6b.json`)

Note: In BioASQ dataset, we don not use all the data. In our methods, we read part of the training data (4b,5b,6b) and divide 20% of the training data for validation.
