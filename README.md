# CCLONE

This Github repository is complementary to our paper **"Identifying cancer cells from calling single-nucleotide variants in scRNA-seq data"**, which is out as [preprint on Biorxiv](https://doi.org/10.1101/2024.02.21.581377).

### Overview
This repository contains two sets of notebooks:
- figure_notebooks/  contains all the notebooks to reproduce the analysis and figures in the paper
- tutorials/  shows and explains how to run the CCLONE analysis pipeline based on the example of patient P1 from the [AML Smart-Seq2 dataset](10.1038/s41467-021-21650-1)
The CCLONE package analysis starts from a anndata object with the REF and ALT count saved as layers. The scripts to generate such an object from a BAM file can be found here:
- scrips/

### Requirements

The toolbox for CCLONE is available as a python package. This package, with additional information on installation can be found [here](https://github.com/ValerieMarot/clonal_tracing_package).

### References

Valérie Marot-Lassauzaie, et al. [Identifying cancer cells from calling single-nucleotide variants in scRNA-seq data](https://doi.org/10.1101/2024.02.21.581377) bioRxiv (2024) 

### Support

If you found a bug, or have a question please open an [issue](https://github.com/ValerieMarot/clonal_tracing_notebooks/issues).
