# Genome Mutation Analysis Pipeline

**Project Author:** Rohit Kumar  
**Authorized by:** Rohit Kumar  

---

## Overview

This project provides a **Python-based pipeline** for analyzing mutations in genomic sequences. The pipeline can compare a **reference genome** with a **sample genome** and detect various types of mutations, including:

- Single Nucleotide Polymorphisms (SNPs)  
- Insertions and Deletions (INDELs)  
- Codon mutations  
- Synonymous and non-synonymous mutations  
- K-mer frequency differences  
- Numeric and image-based representation differences  

It is designed to work with genome sequences in **FASTA/text format**.

---

## Features

1. **Read genome sequences** from text files.  
2. **Clean sequences** (remove spaces, newlines, and convert to uppercase).  
3. **Introduce artificial mutations** for testing purposes (SNPs, INDELs, codon-level).  
4. **Mutation detection techniques**:
    - SNP detection  
    - INDEL detection (with positions)  
    - Codon-level mutations  
    - Synonymous and non-synonymous mutation analysis  
    - K-mer frequency comparison  
    - Numeric array and image-based mutation analysis  
5. **Output**:
    - Total SNPs, INDELs, codon changes, synonymous/non-synonymous mutations  
    - K-mer distance between sequences  
    - Image-based mutation score  

---

## Installation

1. Clone the repository or download the project files.  
2. Install required Python packages:

```bash
pip install numpy matplotlib
