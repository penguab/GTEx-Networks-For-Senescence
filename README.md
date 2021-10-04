# GTEx-Networks-For-Senescence

This directory contains the MEGENA co-networks for 50 human tissues from GTEx database. The donor age was NOT adjusted before network construction. Please refer to age-adjusted dataset in https://github.com/penguab/GTEx-Networks.

Author: Peng Xu

Email: peng.xu@mssm.edu

Draft date: May 16, 2021

## Description

The co-expression networks for different human tissues were uniformly processed by the MEGENA pipeline. The gene expressions were generated from the normalized RNA-seq data from the GTEx (v8) database. 

Four files were shared for the co-expression network results.

GTEx_network.tsv: The co-expression networks for all tissues.

GTEx_module_bigtable.tsv: The module summary information for each co-expression network.

GTEx_module.tsv: The module genes for each co-expression network.

GTEx_module_REACTOME.tsv: The enriched REACTOME pathways for the network modules.

## Citation
For detailed method information, please refer to the Senescence manuscript and the MEGENA publication (Song W.-M., Zhang B. (2015) Multiscale Embedded Gene Co-expression Network Analysis. PLoS Comput Biol 11(11): e1004574.)

## News

5/16/2021: First version released.

