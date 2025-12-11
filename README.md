# PrivEdge_SL
Privacy-aware, optimized Split Learning pipeline (PrivEdge-SL) —  bundle for the manuscript.
This repository contains dataset pointers, notebooks, and meta-selector dataset used to train the meta-model for selecting optimized SL models under device constraints.

top-level files include source code, dataset link, Introductory paper NBAIOT Dataset.pdf, an internal README, and the meta-dataset
# Repository structure 
- source code/ —  training/evaluation scripts, model definitions, utilities.
- Introductory paper NBAIOT Dataset.pdf — dataset description and data source details. 
- nbaiot_meta_selector_dataset_restructured.xlsx — the meta-dataset used to train the meta-selector (features describing model variants and    device metrics). 
-README.md
 # Goal of this repository
- This repository provides the code and supporting data necessary to reproduce the experiments in the PrivEdge-SL manuscript:
- Train baseline and optimized model variants (pruned, quantized, TFLite) for the dataset.
- Generate and/or use the meta-dataset and train the meta-selector that learns to choose the best model variant given device constraints 
- Reproduce aggregate metrics (mean ± std) across repeated runs and perform simple statistical tests.
