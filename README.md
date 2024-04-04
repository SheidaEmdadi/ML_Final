# ML_Final

Student name : Zeinab (Sheida) Emdadi
This project is done as the final exam of the CAS 747 course at McMaster University.
For any enquiries please contac Emdadibz@mcmaster.ca


# Installations
The following instructions are for preparing libraries to run the code on Jupyter Notebook.


```python

! pip  install torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.2.0+cu121.html

```
```python
! pip install  torch_geometric
```

### Other requirements

```python
pygod
networkx
matplotlib
scipy
seaborn
dgl
sklearn
bioinfokit
requests
tqdm
```


## Main Parameters

```python
--dataset                    Anomaly detection dataset (default: disney)
--perturb_percent            Percentages of edges to be added/deleted (default: 0.05)
--seed                       Random Number Seed (default: 42)
--nb_epochs                  Number of epochs (default: 200)
--hidden_dim                 Hidden Dimension Size (default: 16)
--lr                         Learning Rate (default: 0.01)
--l2_coef                    Regularization coefficient (default: 0.01)
--self_loop                  Self-loop flag (default: True)
--preprocess_feat            Preprocess Features (default: True)
--num_neigh                  Number of Neighbors in the State-Space Graph (default: 1)  
```               