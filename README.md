# Search Engine
# Learning to Rank
This repository contains our code for the [Microsoft AI Challenge India 2018](https://competitions.codalab.org/competitions/20616#learn_the_details). Our solution is [Ranked 5th on Public Leaderboard giving 0.7114 MRR Score](https://competitions.codalab.org/competitions/20616#results).<br>

Microsoft organized Microsoft AI Challenge 2018 for India in November 2018. The problem statement was to rank the right response to queries(web) given 10 possible responses.

## Overview of our approach - 
* Fine-tuning [BERT](https://github.com/google-research/bert) with different sequence length
* Ensembling results in different ways

## Public Leaderboard Score of individual models - 

|Total Epochs|Model Decription<br/>(seq. length)|MRR|
|---|---|---|
|1|120 |0.6909|
|1|160 |0.7035|
|2|120 + 120|0.6999|
|2|120 + 160|0.7073|
|3|120 + 120 + 120|0.6981|
|3|120 + 160 + 198|0.7107|
|4|120 + 120 + 120 + 120|0.6899|

### Credits
[Fine-tune an instance of BertForMultipleChoice](https://github.com/huggingface/pytorch-pretrained-BERT/blob/master/examples/run_swag.py) by [Hugging Face](https://github.com/huggingface/pytorch-pretrained-BERT)
