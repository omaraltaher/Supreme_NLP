# Supreme_NLP
Predicting Supreme Court Decisions Using NLP

Abstract

Our work focuses on applying natural language models to Supreme Court case transcripts. The research we present is predicated upon the assumption that there are discernible patterns within the language used in the oral arguments presented at The Court. We experiment with a number of different machine learning techniques to predict case outcomes based on these patterns. Our work investigates the relative merit of bag-of-words and bag-of-vectors representations of the case proceedings, which we use to train Random Forest, Naive Bayes, and Logistic Regression models. 

Introduction

Predicting the behavior of the Supreme Court can have many implications. Political scientists and legal experts have long presented and debated their predictions. The decisions of the court have a major impact on American society. Therefore, the ability to predict those decisions in advance could have a number of uses, depending on the case. Our project will attempt to predict the verdicts of the U.S. Supreme Court based on the oral arguments of the cases. Since court proceedings involve complex arguments, many parties with different speaking styles, and are based on a very large legal code, this topic represents a significant challenge.

See the file "Using NLP to Predict the Behavior of the SCOTUS.pdf" in the current folder for additional information.


Files and Folder Descriptions:

oyez_modeling_clean_with_cross_val.ipynb - Notebook containing final models

oyez_modeling__n-gram_analysis.ipynb - Notebook containing token and error analysis

data_and_etll - Contains all final data files and ETL code used

archive - All previous working notebooks and files


