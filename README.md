# SalivaDB: A Comprehensive Database for Salivary Biomarkers in Humans

Welcome to the official repository and documentation overview for **SalivaDB**, a manually curated database of salivary biomarkers found in humans. This resource serves as a centralized platform to explore diverse biomarkers—including proteins, metabolites, microbes, miRNA, and genes—to advance non-invasive disease diagnosis and prognosis.

**Web Server:** [https://webs.iiitd.edu.in/raghava/salivadb/](https://webs.iiitd.edu.in/raghava/salivadb/)


## Citation

Arora, A., Kaur, D., Patiyal, S., Kaur, D., Tomer, R., & Raghava, G. P. S. (2023). 
**SalivaDB-a comprehensive database for salivary biomarkers in humans.** *Database*, 2023, baad002. 
[https://doi.org/10.1093/database/baad002](https://doi.org/10.1093/database/baad002)

This dataset can also be found on Zenodo at https://doi.org/10.5281/zenodo.20078761

## About the Database

SalivaDB was developed to consolidate scattered information on salivary biomarkers into a single, freely accessible platform. It addresses the need for non-invasive, cost-effective, and precise diagnostic methods by cataloging biomolecules that enter saliva from the blood through various pathways.

The database integrates data from:
* **Primary Literature:** 6,894 entries manually curated from 478 research articles on PubMed.
* **External Repositories:** Data integrated from **SalivaTecDB** (5,776 entries) and the **Human Metabolome Database (HMDB)** (3,151 entries).

## Key Features

### Comprehensive Dataset
* **15,821 total entries** covering 7,729 unique salivary biomarkers.
* **Broad Disease Coverage:** Information related to 201 different diseases and 48 disease categories, including oral cancer, diabetes, and Alzheimer's.
* **Biomolecular Diversity:** Includes proteins (6,067), metabolites (3,987), microbes (2,909), miRNAs (2,272), and genes (586).

### Rich Annotations
Each record includes:
* **Experimental Details:** Analysis methods (e.g., ELISA, mass spectrometry), sampling procedures, and collection methods.
* **Clinical Significance:** Biomarker type (diagnostic or prognostic), regulation status (upregulated/downregulated), and fold change values.
* **Origin & Sequence:** Data on exosomal origin and full sequences for proteins, genes, and microbes (SMILES for metabolites).

### Built-in Tools
* **Search & Browse:** Keyword and advanced search modules with Boolean operator support (AND, OR, NOT).
* **Similarity Search:** Integrated **BLAST** and **Smith-Waterman** algorithms for comparing user-provided sequences against the database.
* **External Linking:** Direct links to PubMed (PMIDs), UniProt, PubChem, miRBase, and NCBI Taxonomy.



## Overview

SalivaDB is organized to provide in-depth information through a user-friendly interface:
1.  **Data Curation:** Rigorous manual curation of literature published between 2017 and 2022, as well as historical data.
2.  **Browsing Modules:** Users can browse by biomarker category, disease type, or exosomal origin to quickly isolate relevant signatures.
3.  **Utility:** Designed for researchers in drug development, bioinformatics, and clinical diagnostics.



## Applications

* **Non-Invasive Diagnostics:** Identifying reliable salivary signatures for early cancer detection or neurological monitoring.
* **Bioinformatics Research:** Utilizing integrated similarity tools for functional annotation of novel protein or miRNA sequences.
* **Therapeutic Development:** Accessing curated data on biomarker regulation to support drug target identification.

## Contact & Authors

**Prof. G.P.S. Raghava**
raghava@iiitd.ac.in
Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT-Delhi), New Delhi, India.

## License

This is an Open Access article distributed under the terms of the **Creative Commons Attribution License (CC BY 4.0)**.
