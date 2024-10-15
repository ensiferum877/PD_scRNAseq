🧬 Project Introduction

This repository demonstrates an automated approach to **identifying**, **acquiring**, and analyzing specific types of publicly available genomic data to support biomarker discovery. The project focuses on **single-cell transcriptomic** data generated from biological fluids, particularly **whole blood** or **peripheral blood mononuclear cells (PBMCs)**, with a specific interest in **Parkinson's disease studies**.

This project touches on the following topics:

1. Programmatic Extraction of data
2. AI-Driven Analysis of Experimental Metadata
3. Single-cell transcriptomics analysis 

In this project, I utilize Python libraries to: 

1. Interact with the Gene Expression Omnibus (GEO) database, perform automated querying based on specific search criteria, and efficiently download relevant dataset metadata.
2. Perform AI-driven data labeling of GEO experimental metadata using Llama 3.2 via Ollama.
3. End-to-end scRNA-seq analysis of 10X genomics data using python libraries such as scanpy and scv-tools.

🧬 Project Walkthrough

**Data Availability**

The data for this project comes from the Gene Expression Omnibus (GEO), a public repository of genomic data. We query GEO for studies related to Parkinson's disease, focusing on single-cell RNA sequencing data from blood or PBMC samples.

🧫 Conclusion
This project demonstrates an efficient, automated approach to identifying relevant genomic studies from GEO and using AI to classify and analyze their metadata. By combining programmatic data extraction with AI-driven metadata analysis, we can more accurately identify relevant datasets, reduce the time and effort required for manual review, and scale our analysis to handle the growing number of publicly available datasets.
