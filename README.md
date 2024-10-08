# TRNanalysis (Transcriptional Regulatory Networks analysis)

## Pipelines and test datasets for TRNs analysis using ChIP-exo and RNA-seq dataset

The pipelines and test datasets provided here are designed for researchers who want to analyze TRNs using ChIP-exo and RNA-seq data. The information of files provided are described below:

### Pipelines : Download .ipynb file (for Google Colab or Jupyter notebook)  
&nbsp;- Protocol-A.4_Classification_of_Regulatory_Roles.ipynb : Python-based automated pipeline for classifying the regulatory roles of each curated peak from ChIP-exo dataset.  
&nbsp;- Protocol-B.1_Data_Pre-processing_for_RNA-seq_Dataset.ipynb : Python-based pipeline for preprocessing of RNA-seq dataset.  
&nbsp;- Protocol-B.2_Calculation_of_Differentially_Expressed_Genes.ipynb : R-based pipeline for calculating the DEGs using DESeq2.  
&nbsp;&nbsp;Using Colab in local runtime : https://research.google.com/colaboratory/local-runtimes.html <br>

### Test datasets : Download the files to your working directory  
&nbsp;- ChIP-exo dataset : Duplicates of mini_ChIP-exo-Ecoli-rpoS-mid-37.fastq.gz (Only R1 file)  
&nbsp;- RNA-seq dataset  
&nbsp;&nbsp;&nbsp; Control samples : Duplicates of mini_RNA-seq_Ecoli_mid-37.fastq.gz (including R1 and R2 files)  
&nbsp;&nbsp;&nbsp; Experimental samples : Duplicates of mini_RNA-seq_Ecoli_del_rpoS_mid-37.fastq.gz (including R1 and R2 files)  
&nbsp;- Others : GenBank, examples of datasheets, curated peak file, etc.
