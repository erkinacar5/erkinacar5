### Hi, I'm Erkin 👋

Bioinformatician at **ETH Zurich (D-BSSE)** in Basel.

I work in R and Python on **single-cell and spatial transcriptomics**, and I've built tools for NGS data in the past.

**Toolbox:** R · Python · Seurat · Scanpy · 10x Visium, Visium HD & Xenium · Snakemake · Docker · Java

####  Teaching: *Spatial Biology of Cancer*, ETH Zurich

Since 2024 I've prepared a new edition of the hands-on R tutorials for this course every year. They take one breast cancer sample from single-cell annotation through Visium analysis, RCTD deconvolution and cell-type co-occurrence, and on to Visium HD.

- **[sbc_course_2026](https://github.com/erkinacar5/sbc_course_2026)**: four tutorials with a preconfigured RStudio Docker image ([`erkinacar5/sboc26`](https://hub.docker.com/r/erkinacar5/sboc26)), so students can skip installing packages
- **[sbc_course_2024](https://github.com/erkinacar5/sbc_course_2024)**: the first edition

####  My students' master's theses

My own GitHub is still fairly quiet. Most of my recent work was done together with my students and lives in their repositories:

- **[Master's thesis: Xenium + CODEX integration framework](https://github.com/lynnarab/master_thesis)** (@lynnarab): an end-to-end integration of Xenium spatial transcriptomics with CODEX spatial proteomics in Crohn's disease biopsies. It aligns the two modalities with Xenium Explorer and defines the steps and tools for the integration: QC, segmentation, joint clustering and annotation.
- **[Master's thesis: Automated, containerized integration workflow](https://github.com/tsochalydia/spatial-multiomics-integration)** (@tsochalydia): builds on the framework above and turns it into a reproducible Snakemake workflow that runs on SLURM in an Apptainer container, with totalVI for the joint RNA + protein embedding. It also improves the alignment of the two modalities by benchmarking registration tools, and introduces metrics that quantify alignment quality.

####  Tools

- **[SortedNucleotideCounter](https://github.com/erkinacar5/SortedNucleotideCounter)**: a Java CLI that counts the reads and nucleotides from a SAM alignment that fall inside GFF features.
