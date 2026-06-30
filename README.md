# bacterial-ngs-variant-calling-pipeline
End-to-end bacterial NGS variant calling pipeline using SRA Toolkit, Bowtie2, Samtools, BCFtools, and IGV.
# Bacterial NGS Variant Calling Pipeline

## Overview

This project demonstrates an end-to-end bacterial whole genome sequencing (WGS) analysis pipeline using publicly available NGS data from the Sequence Read Archive (SRA).

Starting from raw sequencing reads, the workflow includes quality control, adapter trimming, reference genome alignment, variant calling, and visualization of genomic variants.

---

## Dataset Information

* **SRA Accession:** SRR957824
* **Organism:** Escherichia coli K1
* **Sequencing Platform:** Illumina MiSeq
* **Reference Genome:** GCF_000471505.1

---

## Bioinformatics Workflow

1. Retrieval of sequencing data using SRA Toolkit
2. FASTQ generation
3. Quality control using FastQC
4. Adapter trimming using Cutadapt
5. Reference genome download from NCBI
6. Bowtie2 index generation
7. Read alignment using Bowtie2
8. SAM to BAM conversion using Samtools
9. BAM sorting and indexing
10. Alignment statistics generation
11. Coverage analysis
12. Variant calling using BCFtools
13. Variant visualization using IGV

---

## Tools Used

* SRA Toolkit
* FastQC
* Cutadapt
* Bowtie2
* Samtools
* BCFtools
* IGV (Integrative Genomics Viewer)

---

## Results

| Metric                 | Result    |
| ---------------------- | --------- |
| Total Reads            | 3,584,655 |
| Overall Alignment Rate | 81.93%    |
| Properly Paired Reads  | 72.05%    |
| Average Coverage       | 84×       |
| Variants Identified    | 3,162     |

---

## Output Files

* alignment.sam
* alignment.bam
* alignment_sorted.bam
* alignment_sorted.bam.bai
* coverage.txt
* variants.vcf

---

## Skills Demonstrated

* Linux command line usage
* NGS data processing
* Sequence alignment
* BAM file handling
* Variant calling
* Coverage analysis
* Genomic data visualization
* Bioinformatics workflow development

---

