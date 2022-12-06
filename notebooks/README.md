## Notebooks
`./0_ate_weighting.ipynb` obtain causal relationships between the target and each feature, expected output `feats_ate_x13.xlsx`.

`./1_feature_correlations_BNEstimator.ipynb` obtain feature correlations from Bayesian Net, expected output `edge_index_criteo.csv`.

`./2_node_embeddings.ipynb` obtain node embeddings by DeepWalk and Node2Vec, expected output `deepwalk_10d_x13.model` and `Node2Vec_10d_x13.model`. 

`./3_causal_weighting_embedding(10d)_ate(13d).ipynb` perform **Causal-weighted, Equal-weighted and Unweighted Uplift Modelling**.

`./3_causal_without_memory.ipynb` a modified version which creates dataset without saving to disk, perform memory-friendly **Causal-weighted, Equal-weighted and Unweighted Uplift Modelling**.
