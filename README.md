# CellsWells

The DEMO notebook: [main_pipline.ipynb](https://github.com/YuTian8328/CellsWells/blob/main/main_pipline.ipynb)
shows a pipline to obtain node embeddings by training a GNN model.

The pipline consists of:

- generate networkx graphs from raw data
- generate standard tensor graphs for GNN
- customize standard dataset and dataloader for GNN
- train a GNN model
- obtain node embeddings

## Enverionment

- python = 3.10.6
- pytorch_geometric = 2.1.0
- pytorch = 1.12.1
- networkx = 2.8.6
- numpy
- scipy
- pandas
