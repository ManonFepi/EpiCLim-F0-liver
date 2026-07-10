# Metabolomic analysis - EpiClim F0 Liver
Untargeted metabolomic analysis of adult female zebrafish liver samples following developmental exposure to combined climate stressors and PFOS.

## Files
- `.Rmd` — Analysis source code
- `.html` — Rendered analysis
- `.xlsx` files — Input data (metabolite intensities + metadata)

## Analysis pipeline
- Instrument: UHPLC-qTOF-MS (Waters Xevo G3, BEH C18 column)
- Ionization: negative ESI mode
- Preprocessing: MZmine (peak detection, alignment, normalization to internal standards, %RSD filtering on pooled QC)
- Missing value imputation: KNN
- Transformation: log2 + Pareto scaling
- Differential analysis: limma framework, model with condition and exposure
- Pathway enrichment: Mummichog v2 with dre_mtf pathway library (Gamma p-value < 0.05, Hits sig ≥ 3)

## Data
- **Samples**: 41 adult females (n = 5-6 per condition)

## Reproducibility

To reproduce the analyses:
1. Clone this repository
2. Open the .Rmd file in RStudio
3. Ensure the input data files are in the same folder as the .Rmd
4. Install required packages listed in the setup chunk
5. Run all chunks in order or knit the document

Package versions used in this analysis are documented in the sessionInfo output at the end of the rendered HTML.
