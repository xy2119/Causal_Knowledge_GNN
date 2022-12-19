## Here contains Data, Notebooks and Results for the Synthetic Experiments on Datasets of 5 / 9 / 20 Confounders

## Synthetic Experiments

The aim of incorporating synthetic data in the simulation process is to be able to provide an priori evidence to the proposed methodology. The synthetic datasets are generated through [`causalml.dataset.simulate_nuisance_and_easy_treatment module`](https://causalml.readthedocs.io/en/latest/causalml.html#module-causalml.dataset) in CausalML, featured by nuisance components  and an easy treatment effect function.

Three synthetic datasets are generated with 5, 9 and 20 confounders, respectively. Please navigate to the [synthetic_data](./synthetic_data) folder to obtain the necessary datasets before running the notebooks.



<h2 id="folder-structure"> Folder Structure</h2>

      .
      ├── synthetic_data
      │    ├── data.csv              # synthetic dataset with 5 confounders
      │    ├── data_10000_9.csv      # synthetic dataset with 9 confounders
      │    ├── data_10000_20.csv     # synthetic dataset with 20 confounders
      │    └── README.md 
      │    
      ├── synthetic_results
      │      ├── data_10000_x5       
      │      │    ├── causal_embedding(10d)_ate(6d)_.ipynb      # causal-weighted uplift modelling             
      │      │    ├── causal_embedding(10d)_unweighted_.ipynb   # unweighted uplift modelling  
      │      │    ├── synthetic_Node2Vec_10d.model              # node embeddings by Node2Vec
      │      │    ├── synthetic_deepwalk_10d.model              # node embeddings by DeepWalk 
      │      │    ├── Synthetic_feats_ate.xlsx                  # causal weighting of each feature
      │      │    ├── synthetic_edge_index.csv                  # edge list from Bayesian Network
      │      │    ├── train_result_x5.csv                       # results on training set                                   
      │      │    ├── valid_result_x5.csv                       # results on training set   
      │      │    └── README.md    
      │      │    
      │      │
      │      ├── data_10000_x9       
      │      │    ├── causal_embedding(10d)_ate(10d)_x9_.ipynb     # causal-weighted uplift modelling             
      │      │    ├── causal_embedding(10d)_unweighted_x9_.ipynb   # unweighted uplift modelling  
      │      │    ├── Node2Vec_10d_x9.model                        # node embeddings by Node2Vec
      │      │    ├── deepwalk_10d_x9.model                        # node embeddings by DeepWalk 
      │      │    ├── feats_ate_x9.xlsx                            # causal weighting of each feature
      │      │    ├── edge_index_data_9.csv                        # edge list from Bayesian Network
      │      │    ├── train_result_x9.csv                          # results on training set                                   
      │      │    ├── valid_result_x9.csv                          # results on training set   
      │      │    └── README.md    
      │      │    
      │      ├── data_10000_x20       
      │      │    ├── causal_embedding(10d)_ate(10d)_x20_.ipynb     # causal-weighted uplift modelling             
      │      │    ├── causal_embedding(10d)_unweighted_x20_.ipynb   # unweighted uplift modelling  
      │      │    ├── Node2Vec_10d_x20.model                        # node embeddings by Node2Vec
      │      │    ├── deepwalk_10d_x20.model                        # node embeddings by DeepWalk 
      │      │    ├── feats_ate_x20.xlsx                            # causal weighting of each feature
      │      │    ├── edge_index_data_20.csv                        # edge list from Bayesian Network
      │      │    ├── train_result_x20.csv                          # results on training set                                   
      │      │    ├── valid_result_x20.csv                          # results on training set   
      │      │    └── README.md    
      │      │    
      .      .     
      


