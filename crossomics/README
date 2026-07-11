# Cross-omics integration - EpiClim F0 Liver
Pathway-level integration of transcriptomic, metabolomic, and lipidomic analyses of adult female zebrafish liver following developmental exposure to combined climate stressors and PFOS.

## Files
- `.Qmd` — Analysis source code
- `.html` — Rendered analysis with all results
- `.csv`files — Inpit files for metabolomic and lipidomic pathways.

## Analysis pipeline
- Pathway-level integration using shared KEGG BRITE functional categories
- Visualization of convergent and divergent responses across the three omics layers
- Comparison of enriched pathways between transcriptomic, metabolomic, and lipidomic analyses

## Note on reproducibility
This script integrates the results from the transcriptomic, metabolomic, and lipidomic analyses. To avoid duplicating large data files, the script loads intermediate results from a `.RData` file generated during the individual analyses.

To reproduce the analyses:
1. Run each of the individual analysis scripts:
   - `../transcriptomics/EpiCLim_Differential_expression_analysis_Transcriptomic_F0_Liver_Github.Rmd`
   - `../metabolomics/EPICLIM_F0_Liver_Metabolomics_Females.Rmd`
   - `../lipidomics/EPICLIM_F0_Liver_Lipidomic_Females.Rmd`
2. Save the resulting objects with `save.image("epiclim_analysis.RData")`
3. Run this cross-omics script

