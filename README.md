# From Classical Machine Learning to Emerging Foundation Models: Multimodal Data Integration for Cancer Research

<!-- [![arXiv](https://img.shields.io/badge/arXiv-PAPER_ID-b31b1b.svg)](https://arxiv.org/abs/PAPER_ID) -->
[![License: CC BY-NC-4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](LICENSE)


> **Abstract**: Cancer research increasingly relies on integrating diverse data modalities, from genomics to imaging. Foundation models (FMs)—large pretrained deep-learning models—provide powerful new ways to discover biomarkers, enhance diagnosis, and personalize treatments. This review systematically examines multimodal integration strategies in oncology, highlighting the shift from traditional machine learning to advanced FMs. We identify state-of-the-art methods, resources, and challenges, laying essential groundwork for the next generation of large-scale AI models poised to revolutionize cancer research.

![mainfig](./Assets/Figure1.png)
---

### 🎯 Key Contributions

This research offers several key contributions to the field of multimodal data integration in oncology. We provide a comprehensive examination of integration strategies, from classical machine learning techniques to emerging foundation models. By analyzing this transition, we offer insights into the evolution of computational approaches in cancer research. Our holistic view encompasses recent advancements and persistent challenges, particularly in integrating multi-omics data with advanced imaging. We identify state-of-the-art foundation models and curate a list of publicly available resources to support further research. Importantly, we argue that current integrative methods lay the essential groundwork for the next generation of large-scale AI models poised to revolutionize oncology. To our knowledge, this is the first review to systematically map this critical transition, framing it as foundational for the future of AI in cancer research.

- Comprehensive review of multimodal integration strategies in oncology
- Analysis of the shift from traditional machine learning to foundation models
- Holistic view of advancements and challenges in multi-omics and imaging integration
- Identification of state-of-the-art foundation models and public resources
- Argument for current methods as groundwork for future large-scale AI models
- First systematic mapping of the ML to FM transition in oncology

![fig2a](./Assets/Figure2a.png)


### 🧬 Technological Breakthroughs in Cancer Treatment

Following the exploration of deep learning advancements in multimodal cancer research, Figure 2.b highlights the transformative role of imaging and molecular technologies in advancing cancer treatment. These innovations have significantly enhanced our ability to diagnose, characterize, and treat cancer with greater precision, offering new hope for improved patient outcomes.

- **Advanced Imaging Modalities**: Cutting-edge developments in imaging technologies, such as positron emission tomography (PET), magnetic resonance imaging (MRI), and computed tomography (CT), have provided detailed visualizations of tumor structure and behavior, enabling earlier and more accurate detection.
- **Molecular Insights**: Breakthroughs in molecular technologies, including next-generation sequencing (NGS) and single-cell analysis, have revealed the intricate genetic and molecular profiles of tumors, facilitating the design of tailored therapeutic interventions.
- **Data Synergy**: The integration of imaging and molecular data has created a powerful framework for understanding cancer at multiple scales, fostering the development of novel treatment strategies that leverage this combined knowledge.
- **Therapeutic Impact**: These technological advancements have directly contributed to clinical success, with benefits including more effective targeted therapies, reduced treatment-related toxicities, and enhanced monitoring of disease progression.

Together, these breakthroughs underscore the critical role of technology in pushing the boundaries of cancer care. When paired with computational approaches like foundation models, they pave the way for even greater strides in personalized medicine and research innovation.

![fig2b](./Assets/Figure2b.png)


# 📖 Comprehensive Multi-Modal Data Repositories

A critical foundation for advancing multimodal data integration in cancer research lies in the availability of comprehensive, high-quality data repositories. These repositories provide researchers with access to diverse data types—such as genomics, proteomics, transcriptomics, metabolomics, imaging, and clinical metadata—enabling the development and validation of sophisticated machine learning and foundation models. Table 1 presents a curated list of key multi-modal data repositories that are widely used in oncology. These resources not only support the integration of heterogeneous data but also facilitate the discovery of novel biomarkers, the classification of cancer subtypes, and the personalization of treatment strategies. By leveraging these repositories, researchers can train and validate models that capture the full complexity of cancer biology, ultimately driving the next generation of AI-powered oncology tools.

---

### 📚 Comprehensive Multi-Modal Data Repositories

| **Repository**            | **Description**                                                                 | **Data Types**                              | **Cancer Types**                              | **Website**                          |
|---------------------------|---------------------------------------------------------------------------------|---------------------------------------------|-----------------------------------------------|--------------------------------------|
| **The Cancer Genome Atlas (TCGA)** | A landmark cancer genomics program providing molecular characterization of over 20,000 primary cancer and matched normal samples. | Genomics, Transcriptomics, Epigenomics, Proteomics, Clinical metadata | Multiple (e.g., lung, breast, prostate, colorectal) | [TCGA](https://www.cancer.gov/tcga) |
| **Gene Expression Omnibus (GEO)** | A public repository for high-throughput gene expression and genomics data, including microarray and sequencing datasets. | Genomics, Transcriptomics                  | Various (e.g., breast, lung, leukemia, melanoma) | [GEO](https://www.ncbi.nlm.nih.gov/geo/) |
| **Human Protein Atlas (HPA)** | A comprehensive resource mapping the human proteome, including spatial proteomics and transcriptomics data for cancer tissues. | Proteomics, Transcriptomics, Spatial proteomics, Clinical survival data | Over 20 major cancers (e.g., breast, lung, colorectal, prostate) | [HPA](https://www.proteinatlas.org/) |
| **Metabolomics Workbench** | A repository for metabolomics data, including raw and processed datasets from various studies. | Metabolomics (LC-MS, GC-MS, NMR)           | Breast, lung, colorectal, prostate, ovarian, etc. | [Metabolomics Workbench](https://www.metabolomicsworkbench.org/) |
| **European Genome-Phenome Archive (EGA)** | A repository for genomic and phenotypic data, including multi-omics datasets for cancer research. | Genomics, Epigenomics, Clinical metadata   | Breast, colorectal, prostate, lung, hematologic malignancies | [EGA](https://ega-archive.org/) |
| **cBioPortal**            | A platform for exploring, visualizing, and analyzing multidimensional cancer genomics data. | Genomics, Transcriptomics, Clinical metadata | Multiple (e.g., breast, prostate, glioblastoma, leukemia) | [cBioPortal](https://www.cbioportal.org/) |
| **ProteomicsDB**          | A database for proteomics data, including cancer-focused proteomic profiles and drug-target interactions. | Proteomics                                 | Various (e.g., cancer-focused proteomic and PTM profiles) | [ProteomicsDB](https://www.proteomicsdb.org/) |
| **ENCODE (Encyclopedia of DNA Elements)** | A project providing functional annotations of the human genome, including data from cancer cell lines. | Genomics, Epigenomics                      | Breast, lung, colorectal, hematologic malignancies | [ENCODE](https://www.encodeproject.org/) |
| **Synapse (Sage Bionetworks)** | A collaborative platform for sharing and analyzing multi-omics data, including cancer datasets. | Genomics, Transcriptomics, Proteomics, Epigenomics, Clinical metadata | Diverse cancers (e.g., breast, lung, colorectal, prostate) | [Synapse](https://www.synapse.org/) |
| **MetaboLights**          | A database for metabolomics experiments and derived information, including cancer-related studies. | Metabolomics                               | Breast, lung, gastric, renal, liver, colorectal, prostate | [MetaboLights](https://www.ebi.ac.uk/metabolights/) |

---




## Citation
If you use this framework, please cite our work:

```bibtex
@article{muneer2025multimodal,
  title  = {From Classical Machine Learning to Emerging Foundation Models: Review on Multimodal Data Integration for Cancer Research},
  author = {Muneer, Amgad and Waqas, Muhammad and Saad, Maliazurina B. and Showkatian, Eman and et al.},
  journal= {},
  year   = {},
  note   = {}
}
```
