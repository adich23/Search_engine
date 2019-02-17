# Search Engine
# Learning to Rank
This repository contains our code for the [Microsoft AI Challenge India 2018](https://competitions.codalab.org/competitions/20616#learn_the_details). Our solution is [Ranked 5th on Public Leaderboard giving 0.7114 MRR Score](https://competitions.codalab.org/competitions/20616#results).<br>

## Overview of our approach - 
* Fine-tuning Bert with different sequence length
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
