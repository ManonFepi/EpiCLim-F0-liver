# Transcriptomic analysis - EpiClim F0 Liver
Differential expression analysis of adult female zebrafish liver RNA-seq data following developmental exposure to combined climate stressors and PFOS.

## Files
- `.Rmd` — Analysis source code
- `.html` — Rendered analysis
- `.xlsx` files — Input data (counts + metadata)

## Analysis pipeline
- Alignment: nf-core/rnaseq v3.22.2 (GRCz11, Ensembl 113)
- Differential expression: DESeq2 with design ~ exposure + condition
- Effect size shrinkage: ashr
- Thresholds: padj < 0.05, |log2FC| ≥ log2(1.5)
- Enrichment: GSEA on KEGG pathways (padj < 0.25)

## Data
- **Samples**: 28 adult females (n = 3-6 per condition)

## Reproducibility
To reproduce the analyses:
1. Clone this repository
2. Open the .Rmd file in RStudio
3. Ensure the input data files are in the same folder as the .Rmd
4. Install required packages listed in the setup chunk
5. Run all chunks in order or knit the document

Package versions used in this analysis are documented in the sessionInfo output at the end of the rendered HTML.
