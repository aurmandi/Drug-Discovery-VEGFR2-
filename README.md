# ML-Driven VEGFR2 Inhibitor Discovery Pipeline

## Overview
This repository hosts a comprehensive pipeline that integrates machine learning, similarity search, and molecular docking to identify potential inhibitors of the VEGFR2 receptor. Our workflow begins with a curated dataset of biomolecules—each evaluated for their IC50 values—and employs state-of-the-art cheminformatics and predictive modeling to partition molecules into inhibitory (label 1) and non-inhibitory (label 0) classes. The top inhibitory candidates are further expanded through similarity-based searches and rigorously filtered before advancing to molecular docking analyses.

## Project Description
Our pipeline is designed to tackle the complexities of drug discovery in a systematic and data-driven manner. The key steps are as follows:
- **Data Curation & Labeling:** Biomolecules with experimentally determined IC50 values are partitioned by a set threshold. Molecules exhibiting lower (more inhibitory) IC50 values are labeled as 1, while the rest are labeled 0.
  
- **Model Development & Evaluation:** Various machine learning algorithms and multiple SMILES fingerprint descriptors are compared to ascertain the most predictive models.
  
- **Similarity Search Expansion:** The PubChem REST API is used to retrieve hundreds of similar compounds (based on Tanimoto similarity) to the best-performing inhibitors.
  
- **Predictive Filtering & Docking:** The pre-validated model filters these similar molecules to prioritize candidates for molecular docking. Ultimately, the top three molecules with the best predicted binding profiles are selected for further investigation.
  
- **Integrated Reporting:** Detailed summaries and result files are generated at every stage for transparency and reproducibility.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/aurmandi/?
   cd ?
## Requirements
?
?
?
## Usage
?
?
?
## Citation
If you find our work useful for your research or project, please cite it using the following format:

**BibTeX:**
```bibtex
@article{your_paper,
  author    = {Your Name and Co-Authors},
  title     = {Machine Learning-Driven Identification of VEGFR2 Inhibitors: An Integrated Computational Approach},
  journal   = {Journal Name or Preprint Repository},
  year      = {2025},
  volume    = {XX},
  pages     = {XX-XX},
  doi       = {10.XXXX/XXXXX},
}
```

**Alternatively, use:**

**APA:**  
Your Name, Co-Authors. (2025). *ML-Driven VEGFR2 Inhibitor Discovery Pipeline*. GitHub repository. Available at: [https://github.com/yourusername/ML-VEGFR2-Inhibitor-Pipeline](https://github.com/yourusername/ML-VEGFR2-Inhibitor-Pipeline)

If you use our methodology or dataset in your research, please acknowledge our work by citing appropriately.

## Contact
**Email:**
arman.dinarvand100@gmail.com & ?
