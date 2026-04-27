---
layout: page
title:  "Global Soil MAGs Project"
subtitle: ""
date: 2021-09-05  
background: '/img/posts/01smag.jpg'
---

## Overview

In Global Soil MAGs (SMAG) Project, we conducted the first large-scale excavation of soil microbial dark matter by reconstructing 40,039 metagenome-assembled genome bins (the SMAG catalog) from 3,304 soil metagenomes. We identified 16,530 of 21,077 species-level genome bins (SGBs) as unknown SGBs (uSGBs), which greatly expand archaeal and bacterial diversity across the tree of life. The uSGBs identified substantially increased the functional landscape and intra-species genome diversity of the soil microbiome, and provided large proportions of the 43,169 biosynthetic gene clusters and 8,545 CRISPR-Cas genes mined from the SMAG catalog.

## Dataset Download

### Genomes Download
Due to the high cost of long-term maintenance, we have decided to discontinue the use of https://smag.microbmalab.cn/ for data access and downloads. We strongly recommend using the following download options instead:

#### Download from Zenodo (Highly recommended)

The SMAG catalog of the soil metagenomes, SNV catalogs and viruses predicted from SMAG for this publication are available at [Zenodo](https://zenodo.org/records/8223844). 

To facilitate systematic discovery and convenient access to high-quality MAG resources, Dr. Rui Li from the Beijing Institute of Genomics has created an open-source index project, [Awesome MAG](https://github.com/inspirewind/awesome-mag).

SMAG has been included in this project, together with a detailed [Download guide](https://github.com/inspirewind/awesome-mag/blob/main/sources/smag/download.md).

We thank Dr. Rui Li (lirui@big.ac.cn) for organizing and maintaining this helpful community resource.

* All MAGs are estimated to be >= 50% complete and < 10% contaminated
* The MAGs after dereplication meet or exceed the medium-quality level of the minimum information about a metagenome-assembled genome (MIMAG).


#### Download from Cyverse
All the 21,077 MAGs were deposited at [cyverse_21077](https://data.cyverse.org/dav-anon/iplant/home/lucyzju/Caiyu_SMAG_catalog_2023/MAGdrep.tar.gz);
All the 40,039 MAGs were deposited at [cyverse_40039](https://data.cyverse.org/dav-anon/iplant/home/lucyzju/Caiyu_SMAG_catalog_2023/MAG.tar.gz)

## Data Processing Coding

The workflow used to generate the genomes, taxonomic analysis, and functional annotation, alongside the BGCs prediction, pan-genome, SNV annotations, and virus predictions can be found in github repository [Pipeline](https://github.com/Caiyulu-818/SMAG/tree/main/Pipeline).

## Figure Coding

Scripts used to generate the figures are available at [Figure coding](https://github.com/Caiyulu-818/SMAG/tree/main/scripts).

## Figures and Supplementary Table Files 
The source data underlying Figs. 1–6 and Supplementary Figs. 1-6 are provided as Source Data files
and have been deposited in the Figshare database [Data files](https://doi.org/10.6084/m9.figshare.23298791).

## Contacts
The SMAG catalogue remain openly shared and available to all researchers and practitioners in relevant fields, please contact lucy20@zju.edu.cn for further questions or detailed inquiries.

## Publications
Ma, B., Lu, C., Wang, Y. et al. A genomic catalogue of soil microbiomes boosts mining of biodiversity and genetic resources. Nat Commun 14, 7318 (2023).

