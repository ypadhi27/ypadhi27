<h1 align="center">Hi there 👋, I'm Yajnasenee Padhi</h1>

<p align="center">
  <b>Bioinformatics • Computational Drug Design (CADD) • Clinical & Translational Research</b><br/>
  <em>Translating high-throughput omics data and molecular modeling into therapeutic targets and clinically validated biomarkers.</em>
</p>

<p align="center">
  <a href="mailto:ypadhi99@gmail.com"><img src="https://img.shields.io/badge/Email-ypadhi99%40gmail.com-blue?style=flat-square&logo=gmail" alt="Email"/></a>
  <a href="https://github.com/ypadhi27"><img src="https://img.shields.io/badge/GitHub-ypadhi27-black?style=flat-square&logo=github" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Focus-Bioinformatics%20%7C%20Drug%20Design%20%7C%20Clinical%20Research-darkgreen?style=flat-square" alt="Focus"/>
  <img src="https://img.shields.io/badge/Location-Sweden%20%2F%20Nordic-orange?style=flat-square" alt="Location"/>
</p>

---

### 🧬 About Me

I am a bioinformatician and computational biology researcher with a strong multidisciplinary focus spanning **genomics & transcriptomics**, **computer-aided drug design (CADD)**, and **clinical biomarker discovery**. I build reproducible data pipelines, apply rigorous statistical modeling to human clinical datasets, and develop interactive analytics tools to unravel disease mechanisms and identify druggable therapeutic targets.

- 🧬 **Transcriptomics & High-Throughput Omics:** Bulk & single-cell RNA-seq, microarray analysis, differential gene expression, quality control, batch correction, and functional pathway enrichment (GSEA, MSigDB, Reactome).
- 💊 **Computational Drug Discovery & Chemoinformatics:** Target identification & tractability assessment, virtual screening, structure-based molecular docking, ligand-target interaction profiling, and chemoinformatics using RDKit and ChEMBL.
- 🏥 **Clinical Research & Translational Medicine:** Patient stratification, clinical cohort harmonisation, disease stage association modeling, biomarker cross-cohort validation, and survival analysis.
- 💻 **Bioinformatics Software & Data Science:** Production-grade reproducible pipelines (Python, R), leak-free machine learning classification/regression, and interactive web dashboards (Streamlit, Plotly).

---

### 🌟 Featured Portfolio Project

<table>
  <tr>
    <td width="65%">
      <h3><a href="https://github.com/ypadhi27/SkinAge-Atlas">SkinAge Atlas</a></h3>
      <p><b>Reproducible Cross-Cohort Transcriptomic Analysis of Human Skin Ageing with Pathway Analysis and Independent-Cohort Biomarker Validation</b></p>
      <ul>
        <li><b>Research Scope:</b> Models continuous chronological ageing (GSE226189; RNA-seq, N=82) and intra-individual photoaging (GSE38308; microarray, N=42 matched pairs) using live NCBI GEO data.</li>
        <li><b>Pathway Discovery:</b> GSEA PreRank revealed coordinated upregulation of Senescence-Associated Secretory Phenotype (SASP; <code>Protein Secretion</code> NES = +2.37) and downregulation of <code>Cholesterol Homeostasis</code> barrier programs.</li>
        <li><b>Cross-Cohort Machine Learning:</b> Trained regularized Elastic Net regression (MAE = 10.67y, Pearson r = 0.706, p = 1.29e-13) and rigorously benchmarked cross-platform transferability.</li>
        <li><b>Interactive Dashboard:</b> Multi-tab Streamlit & Plotly web app featuring 2D/3D PCA, dynamic volcano threshold filters, and a live patient transcriptomic age gauge simulator.</li>
      </ul>
      <p>
        <a href="https://github.com/ypadhi27/SkinAge-Atlas"><b>Explore Repository →</b></a>
      </p>
    </td>
    <td width="35%" align="center">
      <a href="https://github.com/ypadhi27/SkinAge-Atlas">
        <img src="https://raw.githubusercontent.com/ypadhi27/SkinAge-Atlas/main/results/figures/fig11_predicted_vs_actual_age.png" width="100%" alt="SkinAge Atlas ML Prediction" />
      </a>
      <br/>
      <small><em>Elastic Net Cross-Cohort Age Clock</em></small>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Stack & Methodologies

<table align="center" width="100%">
  <tr>
    <td width="33%" valign="top">
      <h4>🧬 Bioinformatics & Omics</h4>
      <ul>
        <li><b>Data Modalities:</b> Bulk RNA-seq, Microarrays, scRNA-seq</li>
        <li><b>Expression Tools:</b> PyDESeq2, DESeq2, limma, edgeR</li>
        <li><b>Functional Enrichment:</b> GSEAPy, GSEA, clusterProfiler</li>
        <li><b>Databases & Ontologies:</b> NCBI GEO, Ensembl, MSigDB, Reactome, Gene Ontology (GO)</li>
        <li><b>Normalisation & QC:</b> log2-CPM, TMM, PCA, z-score outlier detection</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>💊 Drug Design & CADD</h4>
      <ul>
        <li><b>Chemoinformatics:</b> RDKit, Open Babel, SMILES / InChI handling</li>
        <li><b>Target Discovery:</b> Open Targets Platform, ChEMBL, PubChem, UniProt</li>
        <li><b>Molecular Modeling:</b> AutoDock Vina, PyMOL, Protein-Ligand docking</li>
        <li><b>Druggability Analysis:</b> Pocket detection, pharmacophore screening, Lipinski's Rule of 5</li>
        <li><b>Mechanisms:</b> SASP targets, ECM remodelers, pathway inhibitors</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4>🏥 Clinical & Data Science</h4>
      <ul>
        <li><b>Languages:</b> Python, R, SQL, Bash</li>
        <li><b>Machine Learning:</b> Scikit-Learn (Elastic Net, Random Forests, PCA), Statsmodels</li>
        <li><b>Data Wrangling:</b> Pandas, NumPy, SciPy</li>
        <li><b>Visualization & Dashboards:</b> Streamlit, Plotly, Seaborn, Matplotlib, Tableau, Power BI</li>
        <li><b>Reproducibility:</b> Git, GitHub Actions, Virtual Environments, Nextflow (concepts)</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🔬 Core Research Domains & Competencies

```
  ┌────────────────────────────────────────────────────────────────────────┐
  │                        CORE TRANSLATIONAL CYCLE                        │
  └────────────────────────────────────────────────────────────────────────┘
          ▼                                    ▼                                    ▼
┌───────────────────┐                ┌───────────────────┐                ┌───────────────────┐
│   BIOINFORMATICS  │───────────────▶│    DRUG DESIGN    │───────────────▶│ CLINICAL RESEARCH │
│  & OMICS PROFILING│                │      & CADD       │                │   & BIOMARKERS    │
└───────────────────┘                └───────────────────┘                └───────────────────┘
 • RNA-seq QC & Norm                  • Target Identification              • Patient Stratification
 • Continuous Linear Models           • Molecular Docking (Vina)           • Clinical Cohort Validation
 • GSEA Pathway Signatures            • Chemoinformatics (RDKit)          • Statistical Associations
 • Deconvolution Concepts             • Bioactivity Search (ChEMBL)        • Real-World Data (RWD)
```

---

### 📈 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ypadhi27&show_icons=true&theme=radical&hide_border=true&count_private=true" width="48%" alt="Yajnasenee's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ypadhi27&layout=compact&theme=radical&hide_border=true" width="48%" alt="Top Languages" />
</p>

---

### 📫 Let's Connect!

I am always interested in discussing **translational bioinformatics, computational drug discovery, omics pipeline engineering, and clinical research** opportunities across Sweden, Norway, and greater Europe.

- 📧 **Direct Email:** [ypadhi99@gmail.com](mailto:ypadhi99@gmail.com)
- 💼 **GitHub:** [@ypadhi27](https://github.com/ypadhi27)
- 💬 **Ask me about:** RNA-seq workflows, GSEA pathway enrichment, CADD target identification, clinical data harmonisation, and Python/Streamlit dashboards.
