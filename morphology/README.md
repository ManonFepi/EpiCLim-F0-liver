# Morphology analysis - EpiClim F0 Liver
Morphometric analysis of adult female zebrafish following developmental exposure to combined climate stressors and PFOS.

## Files
- `.Rmd` — Analysis source code
- `.html` — Rendered analysis
- `.xlsx` file — Input data (morphometric measurements + metadata)

## Analysis pipeline
- Endpoints measured: standard length, body weight, liver weight, brain weight, gut weight, gonad weight
- Derived indices: hepatosomatic index (HSI), gonadosomatic index (GSI), brain-somatic index (BSI), Fulton's condition factor (K)
- PCA for global data exploration
- Statistical tests: linear models (lm) and robust linear models (rlm) with residual diagnostics
- Multiple comparisons: emmeans package with Benjamini-Hochberg adjustment
- Factorial analysis: 2×2×2 factorial ANOVA (Type II SS, car::Anova)

## Data
- **Samples**: 92 adult females (n = 10-13 per condition)

## Reproducibility
To reproduce the analyses:
1. Clone this repository
2. Open the .Rmd file in RStudio
3. Ensure the input data files are in the same folder as the .Rmd
4. Install required packages listed in the setup chunk
5. Run all chunks in order or knit the document

Package versions used in this analysis are documented in the sessionInfo output at the end of the rendered HTML.
