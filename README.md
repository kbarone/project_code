# project_code
This repo includes two examples of ML code and one example of data pipelining code.
## Machine Learning Examples
### [bert_topic_analysis.ipynb](https://github.com/kbarone/project_code/blob/main/bert_topic_analysis.ipynb)
This notebook attempts a topic analysis of topics created by ChatGPT after being prompted with public comments on a federal proposed rule change.

### [richter.ipynb](https://github.com/kbarone/project_code/blob/main/richter.ipynb)
This notebook addresses a DrivenData challenge - Richter's Predictor: Modeling Earthquake Damage. There is brief data exploration along with decision tree, random forest and XGBoost model creation. I then use a Bayesian Optimization method to tune the XGBoost model. DrivenData username: kbarone1
## Eng/Pipelining Example
### [gpt_parallel.py](https://github.com/kbarone/project_code/blob/main/eng_example/gpt_parallel.py)
Script that takes in a dataframe of public comments and sends them in parallel to ChatGPT instances for topic tagging. Creates a dataframe with original comments and their associated topics. Within the dataclean_utils module, I did not write the chunk_dataframe or melt_wide_cols functions.
