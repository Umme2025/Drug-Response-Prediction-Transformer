# Drug-Response-Prediction-Transformer
Super-Pathway Transformer for cancer drug response prediction using multi-omics data. The framework constructs hierarchical super-pathways from pathway networks and uses transformer attention with LRP-based interpretability to identify biologically relevant mechanisms in precision oncology.

<h2>Methodology Framework</h2>

<p align="center">
<img src="DeeSuperPath-Model.png" width="500">
</p>
Figure 1. Conceptual architecture of the Super-Pathway Transformer framework for multi-omics cancer drug response prediction.

## Overview
This repository documents the conceptual framework of the Super-Pathway Transformer, a transformer-based model for predicting cancer drug response using multi-omics data and hierarchical pathway representations.  
The framework integrates:

- Multi-omics data (RNA, CNV, mutation, proteomics)
- Pathway-level aggregation (MSigDB Hallmark pathways)
- Super-pathway construction via clustering
- Transformer-based modeling of pathway interactions
- Bayesian linear head for uncertainty estimation
- Layer-wise Relevance Propagation (LRP) for interpretability

---

## Environment Setup

This project was developed using Python and Anaconda.  
Follow the steps below to create the environment using **Command Prompt (CMD)**.
Good catch — you’re right. All steps should use the same heading format. Here is the **corrected version**:

````markdown
### Step 1: Open Command Prompt

Go to project folder using:

```bash
cd path\to\your\project
````

### Step 2: Create Conda Environment

Create a new Conda environment with Python 3.8:

```bash
conda create -n deepathnet_env python=3.8 anaconda
```

### Step 3: Activate Environment

Activate the newly created environment:

```bash
conda activate deepathnet_env
```

### Step 4: Install Required Packages

Install the necessary Python packages:

```bash
pip install numpy pandas scikit-learn matplotlib torch jupyter
```

### Step 5: Launch Jupyter Notebook

Start Jupyter Notebook by running:

```bash
jupyter notebook
```


---

