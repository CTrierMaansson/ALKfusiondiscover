Package: Genefusiondiscover
Title: Identification of EML4-ALK variants using paired-end sequencing
Version: 0.0.1.1
Authors@R: 
    c(person(given = "Christoffer Trier", family = "Maansson", , email = "ctm@clin.au.dk", role = c("aut", "cre"),
           comment = c(ORCID = "0000-0002-3071-3437")),
    person(given = "Emma Roger", family = "Andersen", , email = "201907412@post.au.dk", role = c("ctb", "rev")),
    person(given = "Maiken Parm", family = "Ulhoi", , email = "maiken@oncology.au.dk", role = "dtc"),
    person(given = "Peter", family = "Meldgaard", , email = "petemeld@rm.dk", role = "dtc"),
    person(given = "Boe Sandahl", family = "Sorensen", , email = "b.sorensen@clin.au.dk", role = c("rev", "fnd")))
Description: Paired-end sequencing of cfDNA generated BAM files can be used as input to
  discover EML4-ALK variants. This package was developed using position deduplicated BAM
  files generated with the AVENIO Oncology Analysis Software. These files are made using
  the AVENIO ctDNA surveillance kit and Illumina Nextseq 500 sequencing. This is a targeted 
  hybridization NGS approach and includes ALK-specific but not EML4-specific probes. 
License: `use_mit_license()`, `use_gpl3_license()` or friends to pick a
    license
Encoding: UTF-8
Roxygen: list(markdown = TRUE)
RoxygenNote: 7.2.0
Suggests: 
    knitr,
    rmarkdown
VignetteBuilder: knitr
Imports:
Depends:
  dplyr,
  bamsignals,
  GenomicRanges,
  IRanges,
  Rsamtools
        

See vignettes for details

