# Hannah Yu, Ph.D.

**Clinical Genomics | Bioinformatics | Genomic Data Analysis**

I work across the clinical genomics workflow end to end — producing the data and interpreting it. At Samsung Medical Center I ran WES and RNA sequencing on cancer patient samples; at 3billion I interpreted WES/WGS results and wrote clinical reports. Earlier, at Ohio State, I developed a high-fidelity Oxford Nanopore sequencing strategy (first author, *Advanced Science*, IF 14.5).

The repositories below extend that work into computational analysis: clinical and family genomics, cancer genomics, explainable machine learning on variant data, and workflow automation. I also develop science-education content and data-driven web applications.

**Portfolio:** [hannahyu-source.github.io/portfolio](https://hannahyu-source.github.io/portfolio/)

**Earlier CV site (archived):** [portfolio-canva](https://hannahyu-source.github.io/portfolio-canva/) — the same CV designed in Canva and exported as a single static HTML page, with the profile photo inlined as base64. Superseded by the hand-coded portfolio above; kept online for reference ([repository](https://github.com/hannahyu-source/portfolio-canva)).

---

## 🧬 Genomics & Bioinformatics

### 01 · Family Genome × KEGG Integration
Do family-shared genetic variants connect to disease pathways and drug targets in a way that can be systematically surfaced, not just eyeballed?

- **Focus:** Family genomics · clinical knowledge-base integration
- **Methods:** Python, pandas, ClinVar, KEGG (disease–gene–pathway–drug), pharmacogenomics
- **Key contribution:** Reproducible pipeline integrating 5-member family SNP data with ClinVar (59,501 matched variants) and KEGG (69,546 relations) to surface candidate gene–disease–pathway–drug connections and pharmacogenomic markers, with case studies and explicit validation against source data.
- **Repository:** [kegg-family-genome-analysis](https://github.com/hannahyu-source/kegg-family-genome-analysis)

### 02 · Genomic Variant Machine Learning
Can an explainable ML model shed light on why ClinVar submitters disagree on a variant's clinical significance?

- **Focus:** Genomics × machine learning
- **Methods:** Python, scikit-learn, XGBoost, SHAP, feature engineering, ablation analysis, GroupKFold
- **Key contribution:** Explainable pipeline predicting CADD_PHRED and analyzing ClinVar interpretation-conflict variants, with SHAP-based interpretability, an ablation study isolating feature-engineering gains, and gene-group-held-out (GroupKFold) validation to guard against data leakage.
- **Repository:** [genomic-variant-ML-analysis](https://github.com/hannahyu-source/genomic-variant-ML-analysis)

### 03 · Family-of-Five Genome Dataset
What can a five-member family's raw genotypes reveal about shared variants and inheritance patterns?

- **Focus:** Family genomics · SNP comparison
- **Methods:** Python, pandas, 23andMe-format SNP preprocessing, genotype comparison, visualization
- **Key contribution:** Preprocessed and compared raw genotype data across a father–mother–3 children family to explore shared variants, heterozygosity, and Mendelian inheritance patterns.
- **Repository:** [family-genome-analysis](https://github.com/hannahyu-source/family-genome-analysis)

### 04 · OncoKB Cancer Genomics Analysis
How can a curated cancer-gene knowledge base support hypothesis-generating, variant-level exploration?

- **Focus:** Cancer genomics · knowledge-base interpretation
- **Methods:** OncoKB Cancer Gene List (1,236 genes), MSK-IMPACT / FoundationOne / COSMIC panel cross-reference, LLM-assisted report drafting
- **Key contribution:** Interactive tool over the full OncoKB Cancer Gene List cross-referenced against major clinical sequencing panels, with AI-assisted generation of structured, research-oriented (not diagnostic) variant summaries.
- **Repository:** [oncoKB-cancer-genomics-analysis](https://github.com/hannahyu-source/oncoKB-cancer-genomics-analysis)

### 05 · Genome Weekly Report
Can a weekly literature scan stay useful when nobody curates it by hand?

- **Focus:** Literature curation · workflow automation
- **Methods:** Claude Code skills + scheduled cloud routines, PubMed and bioRxiv APIs, Notion API
- **Key contribution:** Scheduled workflow that gathers the past week's PubMed papers and bioRxiv preprints in genomics/bioinformatics, keeps only what bears on sequencing throughput, cost and QC or on pipelines, algorithms and benchmarks, and publishes a structured Korean report to Notion every Monday. The curation rules live in the Notion page rather than the routine prompt, so the editorial direction can be changed without touching the automation.
- **Repository:** [genome-weekly-report](https://github.com/hannahyu-source/genome-weekly-report)

> Projects 01–04 are research / hypothesis-generating analyses, not clinical diagnostic tools.

---

## 🔬 Science Education & STEM Content

*Translating scientific concepts into accessible educational content and interactive learning experiences.*

**[Himalaya Fossil Science Class](https://github.com/hannahyu-source/Himalaya-Fossil-Science-Class)** — a 13-slide interactive lesson on plate tectonics and marine fossils in the Himalayas, for a middle/high-school science class, with three hands-on activities (strata layering, clay mountain-building, fossil hunt).

**[Star Constellation](https://github.com/hannahyu-source/star-constellation)** — an interactive astronomy web app covering 19 constellations across all four seasons, pairing seasonal star maps with mythology.

---

## 💻 Data & Web Applications

*Applying Python, public datasets, visualization, and lightweight web development to practical data problems.*

**[Bike-Share Demand Analysis](https://github.com/hannahyu-source/bike-share-demand-analysis)** — end-to-end demand forecasting on the UCI bike-share dataset (regression models, feature importance, anomaly detection, train/test generalization checks). A [London companion study](https://github.com/hannahyu-source/London-bike-share-demand-analysis) repeats the methodology on a second city to contrast time-based vs. random train/test splits.

**[STI Surveillance Dashboard](https://github.com/hannahyu-source/STI-surveillance-dashboard)** — a public-health dashboard visualizing weekly STI surveillance trends from KDCA (Korea Disease Control) sample-surveillance data.

**[Starbucks Korea Store Dashboard](https://github.com/hannahyu-source/starbucks-eda)** — an interactive map of 2,134 Starbucks Korea stores (Leaflet + Chart.js) with filters for region, Drive Thru, Reserve and parking, plus search and per-store detail. Ships as a single static HTML file with the store data embedded, so it needs no server or API key.

**[SSG.com Insight Dashboard](https://github.com/hannahyu-source/ssg-dashboard)** — exploratory analysis of 387 discounted product listings collected from SSG.com's internal API: price and discount-rate distributions, brand share, TF-IDF on product names, and price–discount correlation, presented as a static infographic dashboard with a written report.

---

## Skills

**Genomics**
WES/WGS · RNA-seq · Long-read Sequencing (Oxford Nanopore) · Variant Interpretation · Clinical Genomics · Cancer Genomics · Rare Disease Genomics · Family Genomics · ClinVar · KEGG · OncoKB

**Data & ML**
Python · pandas · scikit-learn · XGBoost · SHAP · Statistical Analysis · Data Visualization

**AI-Assisted Workflow**
Claude Code · LLM-assisted literature review · AI-assisted data analysis

---

| Area | Project | Focus |
|---|---|---|
| Genomics | KEGG Family Genome | ClinVar × KEGG × family SNP |
| Genomics ML | Genomic Variant ML | XGBoost, SHAP, generalization |
| Family Genomics | Family-of-Five | inheritance and genotype comparison |
| Cancer Genomics | OncoKB | cancer gene knowledge-base analysis |
| Automation | Genome Weekly Report | PubMed/bioRxiv → Notion, weekly |
| Science Education | Himalaya Fossil | STEM learning content |
| Science Education | Star Constellation | seasonal star maps and mythology |
| Data / Web | Bike-Share Demand | forecasting on public data (D.C. + London) |
| Data / Web | STI Surveillance | KDCA weekly surveillance dashboard |
| Data / Web | Starbucks Korea | 2,134-store interactive map |
| Data / Web | SSG.com Insight | price and discount-rate EDA dashboard |
| Portfolio | Portfolio Site | hand-coded static site, Tailwind build on GitHub Pages |
| Portfolio | Portfolio (Canva) | archived Canva-exported CV page, superseded |
