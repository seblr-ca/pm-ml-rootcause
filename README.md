# Uncovering Process Deviations with Machine Learning

## Overview
This project explores the application of clustering and association rule learning to non-conforming process traces in order to uncover the root causes of deviations from a normative process model. By leveraging Process Mining and Machine Learning, this methodology enables organizations to detect inefficiencies, ensure compliance, and improve process execution.

## Methodology
The analysis follows five main steps:

1. **Process Discovery** – Extract a normative process model from event logs.
2. **Conformance Checking** – Identify non-conforming traces and extract relevant attributes.
3. **Feature Extraction** - Build a trace-level dataframe with key features for ML  
4. **Graph-Based Clustering** – Convert categorical trace attributes into a similarity graph and apply Louvain's community detection.
6. **Association Rule Mining** – Use Apriori to extract frequent patterns and uncover root causes within clusters.

## Structure 
📁 data  
└── 📄 InternationalDeclarations.xes.gz

📁 scripts  
├── 📄 conformance_checking.ipynb  
├── 📄 eda.ipynb  
├── 📄 feature-extraction.ipynb  
└── 📄 process-discovery.ipynb

