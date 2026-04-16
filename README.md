# Hi there, I'm Shweta 👋

### Bioinformatics Analyst | scRNA-seq | EHR & Real-World Evidence Analytics

I am a bioinformatician and data analyst specializing in transcriptomics (bulk and single-cell RNA-seq) and electronic health record (EHR) analytics. I build scalable, reproducible data pipelines in Python, R, and SQL to transform complex, multi-modal healthcare data into actionable therapeutic insights.

* 🔭 **Currently working on:** Automating scRNA-seq quality control workflows and exploring Real-World Evidence (RWE) cohort generations.
* 💻 **Tech Stack:** Python (Scanpy, Pandas), R (Seurat, Bioconductor), SQL (Impala), Bash/Shell.
* ⚙️ **Environments:** High-Performance Computing (HPC), SLURM, Linux, Optum EHR databases.
* 📫 **How to reach me:** syadav21@icloud.com | https://www.linkedin.com/in/syadav21/

---

### 🛠️ Core Competencies
- **Genomics & Transcriptomics:** Upstream/Downstream RNA-seq analysis, Single-cell clustering & UMAP visualization, Differential Gene Expression (DEG), Pathway Analysis (IPA).
- **Healthcare Data Analytics:** ETL pipeline development, large-scale dataset reconciliation, EHR data exploration (ICD/CPT codes, medications).
- **Bioinformatics Engineering:** R package development, git version control, optimizing RAM/compute efficiency for massive datasets (~1M cells).

---

### 📚 Publications & Scientific Impact

1. **Estimating the effect of tissue- and blood-derived cell reference matrices on deconvolving bulk transcriptomic datasets. (https://spj.science.org/doi/10.1016/j.csbj.2025.07.058#sec-8)** — *Computational Structural Biotechnology Journal, 2025* 
   - **My Role:** Integrated bulk RNA-seq/microarray and scRNA-seq data using **Scissor** to identify treatment response-associated cell subpopulations (responder vs. non-responder).
   -  **Key Contributions:** Performed RMA and TMM normalization, comprehensive **scRNA-seq QC** (mitochondrial filtering, UMI normalization, HVG selection, UMAP dimensionality reduction), cell type annotation using **GPTCelltype**, and cell-type-specific pathway enrichment using **Qiagen IPA**.

2. **scCompare: a web app for single-cell RNA sequencing dataset comparisons across multiple auto-immune diseases(https://www.biorxiv.org/content/10.1101/2025.02.04.636484v1)** — *bioRxiv, 2025*
   - **My Role:** Main developer and maintainer of an **R Shiny application** enabling cross-study comparison of Differential Gene Expression (DEG) and pathway enrichment.
   - **Key Contributions:** Engineered the platform to handle **100+ scRNA-seq datasets** spanning multiple autoimmune conditions, ensuring strict data integrity, deployment stability, and post-deployment bug resolution for end-users.

3. **IBDTransDB: a manually curated transcriptomic database for inflammatory bowel disease(https://doi.org/10.1093/database/baae026)** — *Database, 2024*
   - **My Role:** Led data preprocessing/curation for **150+ transcriptomic datasets** and developed a custom **R package** to streamline data access.
   - **Key Contributions:** Built an **R-based QC pipeline** to resolve duplicate/missing genes via imputation, correct Excel date-to-gene-symbol artifacts, and verify normalization. Performed DEG and pathway enrichment, prepared standardized files for the database, and developed an R package that allowed researchers to programmatically query the database and download files, eliminating their need for SQL.

---

### 📊 Highlighted Projects (Below)
*Check out my pinned repositories below for examples of my code, including an end-to-end scRNA-seq pre-processing pipeline and SQL scripts for EHR cohort generation.*
