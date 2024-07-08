# analysis
Analysis of Real and Synthetic Optical Network Topologies 


### Data 
| Data File          | Description                                    | Class     |
|--------------------|------------------------------------------------|-----------|
| mega_analysis.csv  | Contains Graph Metrics for all 105 real topologies  | Real      |
| filename2.csv      | Contains Graph Metrics for Survivable Topologies    | Real      |
| filename.csv       | Contains Graph Metrics for Synthetic small dataset | Synthetic |

### Analysis
| Analysis File           | Description                                                    | Class     |
|-------------------------|----------------------------------------------------------------|-----------|
| summary_stats_correlation | Computed the summary stats and correlations of graph metrics    | Real      |
| clustering              | Computes the clustering on 105 real topologies using k means and SVM | Real      |
| real_syn_similiarity    | Similarity of real and synthetic networks                        | Synthetic |
| large_dataset           | Analysis of large synthetic dataset                              | Synthetic |
