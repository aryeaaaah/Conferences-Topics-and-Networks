# ESANN Conference Network Analysis
 
**Institution:** University of Birmingham, School of Computer Science  

This repository contains the full workflow for analyzing the ESANN conference series (2010–2025), including notebooks, datasets, embeddings, and figures. The project examines topic evolution, co-authorship networks, and collaboration patterns.

## Repository Structure

- `ESANN/` – The research paper (optional, or link to paper repo)  
- `Data Sources/` – Original and processed datasets used for analysis  
- `Notebooks/` – Jupyter notebooks for preprocessing, topic modeling, network analysis, and visualizations  
- `csv files/` – Tabular outputs generated during the analysis  
- `embeddings/` – Precomputed embeddings of abstracts  
- `figures/` – Figures generated during analysis

## Analysis Overview

- **Topic Modeling:** Sentence-BERT embeddings, DBSCAN/HDBSCAN clustering, UMAP for 2D visualization, temporal drift analysis.  
- **Co-authorship Network:** Centrality measures, Louvain community detection, Largest Connected Component analysis.  
- **Key Findings:**  
  - Continuity in Data Mining and Graph Learning  
  - Rapid growth in Deep Learning for NLP and Medical Imaging  
  - Decline of Feature Selection and Spectral Clustering  
  - Fragmented core-periphery network with key hubs and brokers  

---

## How to Reproduce

1. Clone the repository:  
<pre>```bash
git clone https://github.com/aryeaaaah/Conferences-Topics-and-Networks.git </pre>
2. Set up a Python environment and install dependencies (e.g., `pandas`, `numpy`, `scikit-learn`, `umap-learn`, `hdbscan`, `networkx`, `matplotlib`, `sentence-transformers`). 
3. Run the notebooks in `Notebooks/` sequentially to reproduce preprocessing, embeddings, clustering, network analysis, and visualizations.  

