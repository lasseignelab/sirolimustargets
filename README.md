## Purpose. 
Investigate GTEx[(1)](https://pubmed.ncbi.nlm.nih.gov/23715323/)[(2)](https://pubmed.ncbi.nlm.nih.gov/25954001/) tissue-specific expression of the drug targets of sirolimus (aka rapamycin) using signatureSearchData[(3)](https://pubmed.ncbi.nlm.nih.gov/33068417/), Pharos[(4)](https://pubmed.ncbi.nlm.nih.gov/31898878/) (Tclin and Tchem level targets), and Signor[(5)](https://pubmed.ncbi.nlm.nih.gov/36243968/). 

## code/. 
- sirolimus_analyses.Rmd

## data/. 
- gtex_tissue_specificity.txt: Tissue-specific differentially expressed genes from GTEx 
- rapamycin_pharos/queryresults.csv: Pharos Tclin and Tchem targets for sirolimus 
- sirolimus_signor.tsv: Signor interactions for sirolimus 

## figures/. 
- gtex_tissuespecificDEG_sirolimus_heatmap.png 

### Versions  
Platform
```
x86_64-apple-darwin17.0 
R version 4.2.0 (2022-04-22)
```
Packages
```
signatureSearchData      signatureSearch SummarizedExperiment              Biobase 
            "1.10.0"             "1.10.0"             "1.26.1"             "2.58.0" 
       GenomicRanges         GenomeInfoDb              IRanges            S4Vectors 
            "1.48.0"             "1.34.6"             "2.32.0"             "0.36.1" 
        BiocGenerics       MatrixGenerics          matrixStats                 Rcpp 
            "0.44.0"              "1.8.1"             "0.63.0"             "1.0.10" 
          ggalluvial              viridis          viridisLite       ComplexHeatmap 
            "0.12.3"              "0.6.2"              "0.4.1"             "2.12.1" 
             forcats              stringr                dplyr                purrr 
             "1.0.0"              "1.5.0"              "1.1.0"              "1.0.1" 
               readr                tidyr               tibble              ggplot2 
             "2.1.3"              "1.3.0"              "3.1.8"              "3.4.0" 
           tidyverse               readxl                 here 
             "1.3.2"              "1.4.1"              "1.0.1" 
```
