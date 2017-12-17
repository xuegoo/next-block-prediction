# NextBlock prediction in NetsBlox

## Data
The raw dataset can be found at https://github.com/TUDelftScratchLab/ScratchDataset
- my snap analyzer is [here](https://github.com/hamidzr/snap-analyzer)
    - parsing projects into words and sentences.
- tokenize and visualize the data
    - what are the probability distributions
    
## Model
- NGrams with different Ns
- RNN with one hot encoding
    - GRU, LTSM, Regularization (dropout, batch normalizaiton), RELU
- Word embedding, word2vec
    - dimensiality reduction for representation (T-SNE)
- RNN with word2vec embeddings

## Env Variables
- `MAX_SCRIPT_SIZE` defaults to 40
