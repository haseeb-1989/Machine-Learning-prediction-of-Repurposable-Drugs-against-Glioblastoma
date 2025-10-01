# Machine-Learning-prediction-of-Repurposable-Drugs-against-Glioblastoma
This workflow enables virtual screening of small-molecule candidates by combining similarity analysis with both ligand-based and structure-based approaches. It is organized into modular components that support a wide range of cheminformatics tasks.

ML_1. The pipeline queries the ChEMBL database to retrieve target-specific compounds along with their bioactivity annotations (e.g., IC50) and canonical SMILES. The resulting datasets can be used for similarity searches, clustering, and machine-learning model development.

Within the accompanying notebook, compounds tested against the chosen target are collected and the available bioactivity records are filtered. For each molecule, the workflow then computes molecular descriptors, including Lipinski properties and PaDEL descriptors.
