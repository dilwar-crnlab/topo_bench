# analysis
Analysis of Real and Synthetic Optical Network Topologies 


### Data 
| Data File          | Description                                    | Class     | Status | 
|--------------------|------------------------------------------------|-----------|-----------|
| mega_graph_metrics.csv  | Contains Graph Metrics for all 105 real topologies  | Real      | Added ✅ | 
| syn_small_graph_metrics.csv       | Contains Graph Metrics for Synthetic small dataset | Synthetic | Pending 💻 | 

### Analysis
| Analysis File           | Description                                                    | Class     | Status | 
|-------------------------|----------------------------------------------------------------|-----------|----------|
| correlation             | Summary stats, correlations and outliers of graph metrics associated with real topologies    | Real      | Added ✅ | 
| clustering              | Computes the clustering on 105 real topologies using k means and SVM | Real      | Added ✅ | 
| generation              | Generates the topology using SNR BA model | Synthetic-small | Closed Source | 
| analysis                | Structural, physical and spectral analysis of real and synthetic topologies |  Synthetic-small | Pending 💻 | 
| analysis                | Analysis of large dataset | Synthetic-large | Pending 💻  |


If you would like a quick summary of the paper, here is the poster presentatation at TOP conference: 

![final poster top 2025 (1)](https://github.com/user-attachments/assets/73ec4010-44b3-45cb-9bf7-23e1c541b45f)




If you use any of the data provided, please cite our paper:
```
@article{matzner2024topology,
  title={Topology Bench: systematic graph-based benchmarking for core optical networks},
  author={Matzner, Robin and Ahuja, Akanksha and Sadeghi, Rasoul and Doherty, Michael and Beghelli, Alejandra and Savory, Seb J and Bayvel, Polina},
  journal={Journal of Optical Communications and Networking},
  volume={17},
  number={1},
  pages={7--27},
  year={2024},
  publisher={IEEE}
}
```
