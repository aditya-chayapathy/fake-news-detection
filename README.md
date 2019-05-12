# Fake News Detection using Graph Attention Networks

## Description
This project involved training a classifier that helps in distinguishing fake news from real news. Owing to the graph like nature of the relationship between the users and the news articles present in social media, this classifier tries to capture these characteristics with the help of a graph attention network.

## Steps to execute
1. Go to the folder named "codebase".
2. Run the command "pip install -r requirements.txt && python execute_bf_pf.py BuzzFeed".
3. The above command will install all the requirements and run GAT on Buzzfeed dataset.
4. Run the command "python execute_bf_pf.py PolitiFact".
5. The above command will run GAT on PolitiFact dataset.
6. After running the above commands on each dataset, results on training, validation and test set will be displayed.
