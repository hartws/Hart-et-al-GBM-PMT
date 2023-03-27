# Hart-et-al-GBM-PMT
The repository for the manuscript Hart, et al, "Divergent transcriptomic signatures from putative mesenchymal stimuli in glioblastoma cells".

## Accessing data
All RT-qPCRdata used in the generation of this manuscript is available at -----. RNA-seq data is available at -----. TCGA tumor data used to generate Figure 1 is available from cBioPortal. CPTAC data used to generate Figure 1 is avaliable from the NCI proteomic Data Commons. Single-cell RNA sequencing data from Neftel, et al. is available from the Broad Institute Single-Cell Portal.  

## Running the Code
There are five R scripts used to generate the figures in Hart, et al. 
1) G816_RNAseq_analysis 2022.Rmd - this script takes RT-qPCR data and generates plots seen in Figs. 2, S3, and S4, and performs statistical analyses. 
2) TCGA_GBM_PMT.Rmd - this script takes TCGA data and generates the plots seen in Fig. 1A-B and Fig. S2A-B. 
3) CPTAC_GBM_PMT.Rmd - this script takes CPTAC data and generates the plots seen in Fig. 1C-D and Fig. S2C-D. 
4) GBM_scRNA_analysis.Rmd - this script takes Neftel, et al. scRNA-seq data and generates the plots seen in Fig. 1E-F and Fig. S2E-F. 
5) G816_RNAseq_analysis 2022.Rmd - this script takes the RNA-seq data available at [GEO accession number] and generates the plots seen in Figs. 3, S1, S5, and S6.
