## Environment requestion
Scenario Requirements:torch==1.9.0 python==3.7.16 dgl==0.6.1 numpy==1.20.0 pandas==1.3.5 rdkit==2020.9.5.2 torch-geometric==2.2.0

You can run with the below code. 
```python
pip install torch==2.2.1 python==3.8.0 dgl==2.1.0 numpy==1.24.3 pandas==2.0.3 rdkit==2023.9.5 torch-geometric==2.5.2
```
## Installation

Run: 1. Run data_pre_k_fold.py to generate five alternative cross data, python data_pre_k_fold.py. 2. Run train.py to train MCF-DDI Python train.py.
If you want to regenerate a drug-target based similarity matrix, the file under the get_similarity_matric directory is executed.