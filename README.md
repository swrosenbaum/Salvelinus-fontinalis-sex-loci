# Salvelinus-fontinalis-sex-loci

Sam W. Rosenbaum

A bioinformatic workflow exploring genomic sex-determination in Mid-Atlantic brook trout

## Data Overview
32 archived brook trout samples (16 males and 16 females), collected in 2011 from Dry Run, Virginia, were sequenced at ~10x coverage.

### Step 1)
Use [snpArcher](https://github.com/swrosenbaum/snpArcher) to process raw fastq files and obtain QC summary statistics.

### Step 2) 
Use [findZX](https://github.com/swrosenbaum/findZX) to identify sex-linked loci.

