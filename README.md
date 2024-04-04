# CAS747-Final

Student name : Zeinab (Sheida) Emdadi
This project is done as the final exam of the CAS 747 course at McMaster University.
For any enquiries please contact Emdadibz@mcmaster.ca

# Instructions
**Please run all of the cells in the *ML_Project.ipynb* file.** No other modications is needed!

# Installations
This notebook is using these instructions to install the libraries.

```python

! pip  install torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.2.0+cu121.html

```
```python
! pip install  torch_geometric
```

```python
! pip install pygod

```
### Other requirements

```python
pygod
matplotlib
scipy
sklearn
```

# Acknowledgement    
This project is a reimplementation of the GAD-EBM: Graph Anomaly Detection
using Energy-Based Models

```bibtex
@inproceedings{Roy2023gadnr,
  title  = {GAD-EBM: Graph Anomaly Detection using Energy-Based Models},
  author = {Roy, Amit and Shu, Juan and Li, Olivier and Smeets, Jeroen and Zhang, Ruqi and Li, Pan},
  booktitle={New Frontiers in Graph Learning (GLFrontiers), NeurIPS Workshop 2023},
  year   = {2023}
}
```