# Automatic Detection of Depression on COVID-19 Tweets
Project realized by [Eleonora Mancini](https://github.com/helemanc) and [Eleonora Misino](https://github.com/EleMisi) 
as a part of the *Natural Language Processing* exam  of the [Master's degree in Artificial Intelligence @ University of Bologna](https://corsi.unibo.it/2cycle/artificial-intelligence) (A.A. 2019-2020).

The purpose of this project is the analysis of labeling strategies aimed at identifying depression 
phenomena among 
users’ tweets. The tweets used in this analysis refer to a specific period of the COVID19 pandemic. 
In particular, the objective is to try to understand if the strategies studied allow to identify 
evident phenomena of depression among users during the pandemic period. 4 different strategies were 
developed and analyzed. It was not possible to arrive at a robust solution, but this project highlights
some interesting aspects that could be the starting point for a more in-depth analysis.

## Data 
- [COVID19 Tweets](https://www.kaggle.com/datasets/gpreda/covid19-tweets)
- [CLPSych Dataset](https://www.cs.jhu.edu/~mdredze/clpsych-2015-shared-task-evaluation/)


## Project Workflow 
1. COVID19 Tweets 
  - Exploratory Data Analysis 
  - Preprocessing 
  - Topic Modeling: Latent Dirichlet Allocation 
  - Tweets Labelling through 3 strategies that we call TWINT, VADER, NRCLex
  - Labelling Comparison 
  - Unsupervised Analysis (LSA and Clustering)

2. CLPSych Dataset
- Exploratory Data Analysis 
- Features Extraction 
- Tweets Classification 

Please, refer to the [notebooks](https://github.com/helemanc/COVID19-twitter-depression/tree/main/notebooks) folder for 
a more detailed description.

## Running the code 
To reproduce our results: 
- Download the data (please, note that the *CLPsych Dataset* is not publicly available)
- Download the notebooks from [here](https://github.com/helemanc/COVID19-twitter-depression/tree/main/notebooks)
- Run fist the *NLP_Project.ipynb* notebook and then the *CLPsych.ipynb* notebook. 

## Results
A detailed analysis of the results can be found [here](https://github.com/helemanc/COVID19-twitter-depression/tree/main/report).

## Authors
Eleonora Mancini, Eleonora Misino

## License 
This project is licensed under the MIT License - see the [LICENSE](https://github.com/helemanc/COVID19-twitter-depression/blob/main/LICENSE) file for details.
