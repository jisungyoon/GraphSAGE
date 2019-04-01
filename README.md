# PyTorch Unsuperised GraphSAGE Implementation
### Author: Jisung Yoon

This code is based on William L. Hamilton's Simple GraphSAGE (https://github.com/williamleif/graphsage-simple)
Basic reference PyTorch implementation of [GraphSAGE](https://github.com/williamleif/GraphSAGE).
In this code, unsupervised verions of GRAPHSAGE-mean and GRAPHSAGE-GCN are implemented

#### Requirements

pytorch >0.2 is required.

#### Running examples

Execute `python -m graphsage.model` to run the Cora example.
It assumes that CUDA is not being used, but modifying the run functions in `model.py` in the obvious way can change this.
There is also a pubmed example (called via the `run_pubmed` function in model.py).
