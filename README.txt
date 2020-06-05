VARIANT CALLS OF PUBLICLY AVAILABLE SARS-nCov2 GENOMES

This repository encompasses Variant Call Format (VCF) files of publicly available SARS-nCov2 genomes collected from publicly available data sources.

Variant calls from genomic data was performed computationally applying a range of filters to set the Quality Check (QC) criteria. The brief methodology followed is explained as follows,

   Pairwise alignment of genomes to the reference sequence using EMBOSS-Needle global alignment algorithm

   The reference genome used was NC_045512.2, Severe acute respiratory syndrome coronavirus 2 isolate Wuhan-Hu-1, Complete genome

   Filtering genomes based on the number of unknown and degenerate bases, alignment percentage, percentage of gaps and variant count.

   Variant calling using SNP-SITES

 All the filtered VCFs are uploaded and those which have been excluded in the analysis are documented in Excluded.txt provided.


