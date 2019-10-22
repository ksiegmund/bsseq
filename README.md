# bsseq

Goal: is to analyze bisulife sequencing data from .bam files

The first data received are deep-sequencing of 38 amplicon regions. 
We want to call DNA methylation haplotypes from these files.

Step 1. Summarize these 38 amplicon regions.

Step 2. Clip the regions from the C of the first CpG to the G of the last CpG. 

Step 3. Read a .bam file, require the read to cover the entire clipped region, call the (complete) haplotypes, and write to Excel file. 
