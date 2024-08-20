# The *LRRK2* p.L1795F Variant Causes Parkinson’s Disease in the European Population

`GP2 ❤️ Open Science 😍`

DOI: pending

**Last Updated:** August 2024

## Summary
The following repository encompasses all scripts developed and used in the manuscript titled _**"The LRRK2 p.L1795F variant causes Parkinson’s disease in the European population"**_. This study provides evidence that the *LRRK2* p.L1795F variant is pathogenic and causative of Parkinson’s disease (PD) in individuals of European ancestry.

In this research, we identified the p.L1795F variant in 14 European ancestry patients, using data from over 50,000 individuals across multiple cohorts, including GP2, AMP-PD, PDGENEration, and CENTOGENE. All carriers shared a common genetic background, and their clinical symptoms were consistent with other known *LRRK2* variants. Functional studies show that this variant significantly increases *LRRK2* kinase activity, confirming its role as a pathogenic variant. Although rare, the p.L1795F variant should be considered in genetic testing and targeted clinical trials for PD.

Pre-print link: pending

### Helpful Links 
- [GP2 Website](https://gp2.org/)
    - [GP2 Cohort Dashboard](https://gp2.org/cohort-dashboard-advanced/)
- [Introduction to GP2](https://movementdisorders.onlinelibrary.wiley.com/doi/10.1002/mds.28494)
    - [Other GP2 Manuscripts (PubMed)](https://pubmed.ncbi.nlm.nih.gov/?term=%22global+parkinson%27s+genetics+program%22)

## Data Availability

Whole-genome sequencing (WGS) data and genotyping data used in this study are available through the Global Parkinson’s Genetics Program (GP2) and the Accelerating Medicines Partnership - Parkinson’s Disease (AMP-PD). Specific data sources include:

- GP2 WGS data: Available through GP2 (DOI xxx; release 8).
- AMP-PD data: Available through AMP-PD tier 2 access.
- PDGENEration clinical exome data: Available through the Parkinson’s Foundation and GP2 collaboration (DOI xxx; release 8).
- GP2 NBA data: Available through GP2 (DOI 10.5281/zenodo.10962119; release 7).


## Repository Orientation
- The `analyses/` directory includes all analyses discussed in the manuscript.
- The `figures/` directory includes all figures and supplemental figures referenced in the manuscript *(pending publication)*.
- The `tables/` directory includes all tables and supplemental tables referenced in the manuscript *(pending publication)*.

---

### Analyses

Languages: Bash, R, Python


| Analysis                    | Description                                                                                                                                                                                          |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 00_variant_screening            | Screen the LRRK2 p.L1795F carriers in GP2 WGS, clinical exome and NBA dataset |
| 01_statistical_analyses         | Perform the association of LRRK2 p.L1795F with PD |
| 02_ibd_inference                | Infer the shared haplotype of LRRK2 p.L1795F carriers using NBA data |


---
### Figures and Supplemental Figures

*(pending publication)*

---
### Tables and Supplemental Tables 

*(pending publication)*

---
## Software 

| Software           | Version(s) | Resource URL                                               | RRID          | Notes                                                                           |
|--------------------|------------|------------------------------------------------------------|---------------|---------------------------------------------------------------------------------|
| DeepVariant        | 1.6.1      | [DeepVariant](https://github.com/google/deepvariant)       | NA            | Variant calling for whole-genome sequencing data                                |
| GLnexus             | 1.4.3      | [GLnexus](https://github.com/dnanexus-rnd/GLnexus)         | NA            | Used for joint-genotyping of WGS and WES data                                    |
| Ensembl VEP        | 111        | [VEP](http://www.ensembl.org/info/docs/tools/vep/index.html) | SCR_007931    | Variant annotation                                                              |
| KING               | 2.3.0      | [KING](http://people.virginia.edu/~wc9c/KING/)             | SCR_009251    | Infers relatedness up to the second-degree relatives                             |
| GenoTools          | 1.2.3      | [GenoTools](https://github.com/GP2code/GenoTools)         | NA            | Used for genetic ancestry determination and quality control                      |
| NeuroBooster Array | 1.0        | [Pre-print](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10659467/)                                                         | NA            | NBA genotyping tool                           |
| Beagle             | 5.4        | [Beagle](https://faculty.washington.edu/browning/beagle/beagle.html) | NA            | Phasing of genotyping data for European population                               |
| hap-ibd            | 1.0.0      | [hap-ibd](https://github.com/browning-lab/hap-ibd)         | NA            | Searches for identical-by-descent segments across carriers   |