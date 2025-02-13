## This repo includes the snakemake pipeline workflow to run on short-read technology such as Illumina, Element, Pacbio onso. For the QC, GA4GH QC pipeline were run on the BAM files to generate the QC metrics for the short-read technology data.


**HG008-T**

The snakemake workflow for the tumor data includes fastQC, BWA-MEM, samtools index, mosdepth, samtools stats and multiQC. The mosdepth wrapper was used to calculate the chr4 mosepth diploid and halploid mean coverages for the data.

**GA4GH QC pipeline** 
[GA4GH_QC_pipeline](https://github.com/c-BIG/NPM-sample-qc/tree/v0.11.0)

For the QC, GA4GH QC pipeline were used to generate the QC metrics for the short-read data

**HG008-N-D and HG008-N-P**

The snakemake workflow for the tumor data includes fastQC, BWA-MEM, samtools index,samtools stats and multiQC. The mosdepth wrapper was used to calculate the chr4 mosepth diploid and halploid mean coverages for the data. 

Note: we dont use mosdpeth wrapper here since we only calculate chr4 mosdepth diploid and haploid mean coverages for the Tumor samples only so workflow doesn't include mosdepth wrapper here

**GA4GH QC pipeline** 
[GA4GH_QC_pipeline](https://github.com/c-BIG/NPM-sample-qc/tree/v0.11.0)

For the QC, GA4GH QC pipeline were used to generate the QC metrics for the short-read data


