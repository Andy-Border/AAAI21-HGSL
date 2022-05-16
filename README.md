# HGSL
Source code of AAAI submission "Heterogeneous Graph Structure Learning for Graph Neural Networks"
# Requirements
## Python Packages
- Python >= 3.6.8
- Pytorch >= 1.3.0
## GPU Memmory Requirements
- ACM >= 8G
- DBLP >=5G
- Yelp >=3G 
# Usage
Take DBLP dataset as an example:
python train.py --dataset='dblp' 

# FAQ
## Code of preprocessing data?
Please kindly note that the data is originally preprocessed by GTN project (https://github.com/seongjunyun/Graph_Transformer_Networks). 
_I received quite a lot email asking me about the dataset. I will not respond to them anymore as I cannot provide the code._

## How to generate semantic embeddings?
The semantic embeddings, i.e. $\mathcal{Z}$ in the paper, are generated by metapath2vec algorithm. Users may refer to https://github.com/dmlc/dgl/tree/master/examples/pytorch/metapath2vec for an implementation.
