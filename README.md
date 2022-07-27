# Genefusiondiscover

An R/Bioconductor package to evaluate BAM files and identify genefusions, such as EML4-ALK

> This package was created in order to increase the sensitivity of EML4-ALK detection from commercially available NGS products such as the AVENIO (Roche) pipeline. Paired-end sequencing of cfDNA generated BAM files can be used as input to discover EML4-ALK variants. This package was developed using position deduplicated BAM files generated with the AVENIO Oncology Analysis Software. These files are made using the AVENIO ctDNA surveillance kit and Illumina Nextseq 500 sequencing. This is a targeted hybridization NGS approach and includes ALK-specific but not EML4-specific probes. The package includes six functions. The output of the first function, `EML4_ALK_detection()`, is used to determine whether EML4-ALK is detected and serves as input for the next four  exploratory functions characterizing the EML4-ALK variant. The last function `EML4_ALK_analysis()` combines the output of the exploratory functions. To serve as examples, this package includes BAM files representing the EML4-ALK positive cell line H3122 and the EML4-ALK negative cell line, HCC827.

## Highlights
Genefusiondiscover is under active development. In the future the package will include more genefusions such as ROS1 and RET, as well as other ALK fusionpartners

## Installation

Latest version can be installed through github

```{r}
if (!require(devtools)) install.packages('devtools')
library(devtools)

install_github("CTrierMaansson/Genefusiondiscover", build_vignettes = TRUE)
library(Genefusiondiscover)

```

## Vignettes

See the 
