**Hierachical Attention Networks**

An efficient pytorch implementation of Hierarchical Attention Networks model proposed in the paper https://www.cs.cmu.edu/~hovy/papers/16HLT-hierarchical-attention-networks.pdf

Repository includes all supporting files along with the model as described below:

- data.py - Reads data from a pandas dataframe containing fields 'text' and 'label'. Expects the data to be split into train, test and val each into separate csv files.
- util.py - Contains batcher methods, embedding methods etc.
- train.py - Containts the main training loop
- main.py - Specify data paths, embedding files and other settings here.
- model.py - Contains the model broken down into different parts.


Dependencies

- gensim
- sklearn
- pytorch
