# Sex-Chromosome Dosage Analysis - Domestic Cattle

**Course:** Cell and Molecular Biology  
**Activity:** Sex-Chromosome Dosage in a Selected Animal Nuclear Genome Using NCBI, Galaxy, and R  
**Species:** Domestic Cattle (*Bos taurus*)  
**Genome Assembly:** ARS-UCD2.0 (GCF_002263795.3)  
**WGS Run:** SRR5753432  
**Assembly BioSample:** SAMN03145444  
**WGS BioSample:** SAMN03145444  
**Sex System:** XX/XY  
**Same Donor:** Yes

## Project Overview

This study aims to determine the possible sex-chromosome composition of a selected domestic cattle (*Bos taurus*) individual through the analysis of whole-genome sequencing (WGS) data.

The procedure involves obtaining a chromosome-level reference genome from NCBI, aligning the sequencing reads and determining chromosome coverage using Galaxy, and processing and visualizing the resulting data through R.

The analysis focuses on evaluating the read depth of the X chromosome relative to the median coverage of selected autosomes. The Y chromosome is also considered to provide supplementary evidence in interpreting the animal's sex-chromosome complement.

### Study Question

Based on the chromosome read-depth measurements of the selected *Bos taurus* sample, can its sex-chromosome composition be classified as XX-like or XY-like, and is this interpretation consistent with the sex information available in its NCBI BioSample record?

## Species/Sex-Chromosome System

The species selected is domestic cattle (*Bos taurus*).

Cattle - XX/XY sex-determination system, in which:
- Females typically possess two X chromosomes (XX).
- Males typically possess one X chromosome and one Y chromosome (XY).

The chromosome-level reference genome, ARS-UCD2.0 (GCF_002263795.3), includes an identified X chromosome. The X chromosome will be examined in comparison with selected autosomes to estimate the sex-chromosome complement of the WGS sample.

## 3. NCBI Data Sources

### Reference Genome

- Species: *Bos taurus* (Domestic cattle)
- Assembly name: ARS-UCD2.0
- Assembly accession: GCF_002263795.3
- Assembly BioSample: SAMN03145444
- Assembly level: Chromosome

Links:
- [NCBI Genome Assembly](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_002263795.3/)
- [NCBI Assembly Report](https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/002/263/795/GCF_002263795.3_ARS-UCD2.0/GCF_002263795.3_ARS-UCD2.0_assembly_report.txt)

### Whole-Genome Sequencing (WGS) Data

- Species: *Bos taurus*
- WGS Run accession: SRR5753432
- WGS BioSample: SAMN03145444
- Sequencing strategy: WGS
- Sequencing platform: PacBio RS II
- Library layout: Single-end
- Same donor: Yes

Links:
- [NCBI SRA Run](https://www.ncbi.nlm.nih.gov/sra/SRR5753432)
- [NCBI BioSample](https://www.ncbi.nlm.nih.gov/biosample/SAMN03145444)




