# DNA methylation signature of smoking in lung cancer is enriched for exposure signatures in newborn and adult blood

## Citation Information
Bakulski KM, Dou J, Lin N, London SJ, Colacino JA. 2019. DNA methylation signature of smoking in lung cancer is enriched for exposure signatures in newborn and adult blood. Scientific Reports. PMID: 30872662, PMCID: PMC6418160. DOI: 10.1038/s41598-019-40963-2

This Github repository contains the data management and analytic scripts to produce the following manuscript:[DNA methylation signature of smoking in lung cancer is enriched for exposure signatures in newborn and adult blood](https://pubmed.ncbi.nlm.nih.gov/30872662/)

## Abstract
Smoking impacts DNA methylation genome-wide in blood of newborns from maternal smoking during pregnancy and adults from personal smoking. We compared smoking-related DNA methylation in lung adenocarcinoma (61 never smokers, 91 current smokers, and 238 former smokers) quantified with the Illumina450k BeadArray in The Cancer Genome Atlas with published large consortium meta-analyses of newborn and adult blood. We assessed whether CpG sites related to smoking in blood from newborns and adults were enriched in the lung adenocarcinoma methylation signal. Testing CpGs differentially methylated by smoke exposure, we identified 296 in lung adenocarcinoma meeting a P < 10-4 cutoff, while previous meta-analyses identified 3,042 in newborn blood, and 8,898 in adult blood meeting the same P < 10-4 cutoff. Lung signals were highly enriched for those seen in newborn (24 overlapping CpGs, Penrichment = 1.2 × 10-18) and adult blood (66 overlapping CpGs, Penrichment = 1.2 × 10-48). The 105 genes annotated to CpGs differentially methylated in lung tumors, but not blood, were enriched for RNA processing ontologies. Some epigenetic alterations associated with cigarette smoke exposure are tissue specific, but others are common across tissues. These findings support the value of blood-based methylation biomarkers for assessing exposure effects in target tissues.

## Funding
Dr. London is supported by the Intramural Research Program of the NIH, National Institute of Environmental Health Sciences (ZO1 ES49019). Mr. Dou and Dr. Bakulski were supported by grants from the National Institute of Environmental Health Sciences and the National Institute of Aging (R01 ES025531; R01 ES025574; and R01 AG055406). Dr. Colacino is supported by grants from the National Institute of Environmental Health Sciences (R01 ES028802 and P30 ES017885).

## Data Availability
The Cancer Genome Atlas data that support the findings of this study are publicly available through the National Cancer Institute Genomics Data Commons Portal (https://portal.gdc.cancer.gov/). The findings in newborn blood3 and adult blood5 are available in the supplementary material for the respective manuscripts.

## Script Files

This is a [workflowr](https://github.com/jdblischak/workflowr) project.

*analysis* folder contains codes producing this project

smoking_luad.Rmd: data cleaning and data analysis

*docs* folder contains the relative libraryies and html file of code 
