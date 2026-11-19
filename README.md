# Single-Cell RNA-seq Reanalysis: Lethal COVID-19 Immune Profiling

End-to-end single-cell transcriptomic reanalysis investigating immune cell populations, clustering, and differential gene expression signatures associated with severe/lethal COVID-19.

### 📄 Full Analysis Report
* **[View Complete PDF Run & Code Walkthrough](reports/covid19_scrna_full_analysis.pdf)** *(Includes QC filtering, normalization, dimensionality reduction, clustering, and marker gene tables)*

---

### 📊 Key Results Preview

#### 1. Cell Type Clustering (UMAP)
![UMAP Clustering](figures/umap_clusters.png)

#### 2. Canonical Marker & Differential Expression
![Marker Genes](figures/marker_dotplot.png)

---

### 🛠️ Pipeline Summary
* **Quality Control & Preprocessing:** Mitochondrial gene filtering, doublet/low-count removal, normalization, and highly variable gene selection.
* **Dimensionality Reduction & Clustering:** PCA, neighborhood graph construction, UMAP embedding, and Leiden/Louvain clustering (`Scanpy`).
* **Differential Expression & Annotation:** Cluster marker identification and cell-type annotation across immune subsets.
