# Variant-Calling_BASH_Pipeline
Variant Calling Pipeline using GATK4
Germline Variant Calling Pipeline (GATK4 Best Practices).

This Bash script automates a human whole-genome germline variant calling workflow following the GATK4 Best Practices
. It downloads raw reads, prepares reference data, performs quality control, alignment, duplicate marking, base quality score recalibration (BQSR), and finally calls SNPs and INDELs using GATK’s HaplotypeCaller.


Credit to Khushbu Patel:
⚡ **Inspired by** [kpatel427’s bioinformatics pipelines](https://github.com/kpatel427) 

Main steps:

1-Download paired-end FASTQ reads and the hg38 reference genome

2-Perform read quality control with FastQC and fastp

3-Align reads to the reference genome using BWA-MEM

4-Mark duplicates and recalibrate base quality scores with GATK4

5-Collect alignment metrics

6-Call and separate variants (SNPs & INDELs)

Tools used:
FastQC, fastp, BWA, Samtools, GATK4

<a href="https://creativecommons.org">Untitled</a> © 1999 by <a href="https://creativecommons.org">Jane Doe</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

