# Master Thesis: Unsupervised Learning for Detection of Rare Driving Scenarios

This project explores unsupervised learning to identify rare driving scenarios using multivariate time series data from autonomous vehicle perception systems. The main technique is Deep Isolation Forest, a state-of-the-art method for detecting contextual anomalies.

Part of this work has been accepted for publication at the **IEEE Intelligent Transportation Systems Conference (ITSC) 2025**, to be held in **Gold Coast, Australia**.

## 📁 Repository Contents

- [`master_thesis.pdf`](./master_thesis.pdf)  
  Final version of the master thesis report detailing the research, methodology, experiments, and findings.

- [`thesis_paper.pdf`](./thesis_paper.pdf)  
  A condensed version of the thesis, written in the format of a conference paper. This version has been accepted for publication at IEEE ITSC 2025.

- [`thesis_experiment_main.ipynb`](./thesis_experiment_main.ipynb)  
  Main experimental notebook combining a mix of **continuous** and **categorical** features for anomaly detection. This notebook implements the full version of the Deep Isolation Forest pipeline and includes complex feature processing and visualization.

- [`thesis_experiment_simple.ipynb`](./thesis_experiment_simple.ipynb)
  A baseline experiment using **only one continuous signal** and **multiple categorical features**. This simplified notebook demonstrates the core concept of contextual anomaly detection in a minimal and interpretable setting.
