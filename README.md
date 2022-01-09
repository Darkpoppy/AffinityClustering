# Affinity Clustering

This repository provides the implemention of the Affinity Clustering method for partitioning sparse graphs introduced by [Bateni et al. 2017](https://papers.nips.cc/paper/2017/hash/2e1b24a664f5e9c18f407b2f9c73e821-Abstract.html). Apache Spark is used for performing the parallel computation.

The algorithm, along with testing code is provided in the [following Jupyter Notebook](/affinity_sparse_graphs_version2.ipynb).

## Requirements
- Python 3.9
- PySpark 3.0.1
- numpy1.20.1
- networkx 2.5
- matplotlib 3.3.4
- sklearn
- scipy 1.6.1
- jupyter 

## Usage
Install the required dependencies
```bash
pip install -r requirements.txt
```
Recomended: use a dedicated virtual env or anaconda for easy dependency management
