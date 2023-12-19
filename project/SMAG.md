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

### Web-based user interface

All the quality and taxonomy information of the genomes in SMAG catalog can be viewed at web-based user interface [SMAG_interface](https://smag.microbmalab.cn/)

### Genomes Download

#### Download from SMAG_interface

The soil metagenome-assembled genome sequences of SMAG project can be downloaded in fasta format through [SMAG_40039](https://bma-public.s3.cn-northwest-1.amazonaws.com.cn/SMAG/MAG40039.tar.gz); [SMAG_40039_MD5](https://bma-public.s3.cn-northwest-1.amazonaws.com.cn/SMAG/MAG40039.md5);
SMAG MAGs after dereplication (N=21,077) was deposited at [SMAG_drep_21077](https://bma-public.s3.cn-northwest-1.amazonaws.com.cn/SMAG/magdrep.tar.gz); [SMAG_drep_21077_md5](https://bma-public.s3.cn-northwest-1.amazonaws.com.cn/SMAG/magdrep_21077.md5);
The uSGBs (N=16,530) can be downloaded at [16,530_uSGBs](https://bma-public.s3.cn-northwest-1.amazonaws.com.cn/SMAG/mag16530.tar.gz); [16530_uSGBs_md5](https://bma-public.s3.cn-northwest-1.amazonaws.com.cn/SMAG/mag16530.md5);
The virus identified from SMAG can be downloaded from [mag_virus](https://bma-public.s3.cn-northwest-1.amazonaws.com.cn/SMAG/magvirus.fa)

#### Download from Zenodo

The SMAG catalog of the soil metagenomes, SNV catalogs and viruses predicted from SMAG for this publication are available at [Zenodo](https://zenodo.org/records/8223844). 
To upload the large gz file, we split it into smaller file with the prefix "mag.tar.gz", downloaders can use the `cat ./mag.tar.gz* > mag.tar.gz; tar -xjvf <mag.tar.gz>` to process the MAGs.


## Data Processing Coding

The workflow used to generate the genomes, taxonomic analysis, and functional annotation, alongside the BGCs prediction, pan-genome, SNV annotations, and virus predictions can be found in github repository [Pipeline](https://github.com/Caiyulu-818/SMAG/tree/main/Pipeline).

## Figure Coding

Scripts used to generate the figures are available at [Figure coding](https://github.com/Caiyulu-818/SMAG/tree/main/scripts).

## Figures and Supplementary Table Files 
The source data underlying Figs. 1–6 and Supplementary Figs. 1-6 are provided as Source Data files
and have been deposited in the Figshare database[Data files](https://doi.org/10.6084/m9.figshare.23298791).

## Contacts
Other associated data supporting the findings are available from the corresponding author(bma@zju.edu.cn) upon reasonable request. Also you can contact lucy20@zju.edu.cn for details.

## Publications
Ma, B., Lu, C., Wang, Y. et al. A genomic catalogue of soil microbiomes boosts mining of biodiversity and genetic resources. Nat Commun 14, 7318 (2023).

