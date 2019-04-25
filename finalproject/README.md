# Final Project

## Instructions

This repository is a stub for your final project. Fork it as a template for your project, and develop your code in the forked repository. After you fork the repository, please enable the issue tracker in the repository settings so that others in the class (including the professor) can provide feedback. To submit the project, send a pull request to the original repository.

Expand on the readme questions below to provide an overview of the goals, background, and challenges for the final project. You can delete the questions as you write text that answers them, or leave the prompts in place. You can also delete this instruction section of you like.

Add all code to your project repository, including shell scripts, R analyses, python, etc.

Do not commit large data files to the repository. Provide paths to where they can be downloaded if they
are from public sources, or track them with [git-lfs](https://git-lfs.github.com).

## Introduction

This is a final project for the [Comparative Genomics](https://github.com/Yale-EEB723/syllabus) seminar in the spring of 2019. In my project, I seek to answer questions related to a gene cluster in Bacteroides encoding a bacteriocin likely used as a competitive factor to persist in gut microbial landscapes.

## The goal

I seek to explore one or more of the following specific problems:

1. to better understand gene cluster occurrence across phylogenies and to determine whether they are gut bacteria restricted

2. to determine the co-occurrence patterns of the genes in question 1466, 1465, 1464, and 2671

3. to identify the genomic island boundaries for this gene cluster

4. to determine amino acid conservation across homologues

5. to understand co-occurrence patterns of other genes specific to cluster (+) and cluster (-) genomes


## The data

I plan to use metagenomic data referenced and used in several recent microbial metagenomics publications. A representative source is the data at the following link:

http://segatalab.cibio.unitn.it/data/Pasolli_et_al.html


(downloaded the fasta file into PACTRIC - genomes are already binned into species-level genome bins)

from the following source:

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6349461/

Data from the reconstructed genomes will be used.

Below are other sources with datasets of potential use:

https://www.nature.com/articles/s41587-018-0009-7

https://www.nature.com/articles/s41587-018-0008-8

https://www.nature.com/articles/s41586-019-0965-1


## Background

Motivation for the project....
The Goodman Lab at the Yale Microbial Sciences Institute has identified a novel bacteriocidin used in competition between gut bacterial species. Understanding more about the genes associated with this bacteriocin and associated proteins will be important to uncovering its distribution among gut commensals and pathogenic species. It will enable the uncovering of co-occurring genes and phenotypes that can contribute to a collective fitness profile. Knowing what makes microorganisms capable of thriving in the hyper-competitive gut environment will be critical to engineering beneficial probiotic strains or cocktails for disease treatment and prevention.

How it fits in with other work...



What the reader needs to know to understand the project...

Bacteriocins are ribosomally produced peptides secreted by a bacterial strain or species to help establish them in a community niche. Bacteriocins can take the form of colonization factors that help the host occupy a competitive niche, or can act to directly kill competitors. The producer of the protein will have a specialized immunity mechanism that prevents it from experiencing these toxic effects. Bacteriocins can also function as signaling peptides to foster inter-bacterial or bacteria-host immune crosstalk. (1)


## Methods

Methods to be used are still being determined alongside narrowing down the above questions - determining which will be most feasible to approach based on the methods available.

1. uploaded metagenomic data to PATRIC

2. uploaded four fasta files for the genes of interest from NCBI to PACTRIC

3. BLASTED 2671 nucleotide sequence against all B. fragilis species genomes
- identified 8 strains that have the gene (99-100% identity)
- gene product is defined as Clostripain-related protein

## Results


## Assessment

Was it successful in achieving the initial goal?

What are the main obstacles encountered?

What would you have done differently?

What are future directions this could go in?

## References

[1] 2012 Review on bacteriocins in the microbiota: https://aem.asm.org/content/78/1/1
