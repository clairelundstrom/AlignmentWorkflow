# AlignmentWorkflow

This is an example workflow for analyzing NGS data. The workflow takes raw data (.fastq) and processes through the following workflow: 

1) quality assessment, filtering, trim adaptors (fastp)
2) alignment to reference genome (bowtie2)
3) index, sort, and binary compress reads (samtools)

This is a minor change, to include information about Snakemake!!

