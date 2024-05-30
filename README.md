# 2024_mtCN_stepwise_regression

### Goal: Build a stepwise linear regression model to predict mtCN based on protein abundance measured by TMT proteomics 

### Input file: ccle176.mtCN_and_TMT.raw_vals.complete_obs.txt
### Columns: 176 cell lines from CCLE (Cancer Cell Line Encyclopedia)
### Rows: First row is mtDNA copy number (mtCN, estimated from whole genome sequence data), other 5153 rows are proteins
### Values: Protein abundance measured by TMT proteomics in each cell line (or mtCN for first row)

### Contents: Stepwise linear regression was performed using the R package leaps (regsubsets, nvmax=3, method="forward")

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/deed.en). You are free to share or adapt the material for non-commercial purposes.
