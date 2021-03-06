[![Travis-CI Build Status](https://travis-ci.org/waldronlab/MicrobiomeWorkshop.svg?branch=master)](https://travis-ci.org/waldronlab/MicrobiomeWorkshop)

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

# Working with open-source Human Microbiome Project Data phases 1 (HMP) and 2 (iHMP): Efficient Data Access and Analysis Workflow

# Instructors names and contact information

1. Levi Waldron (@LeviWaldron1), Graduate School of Public Health and Health Policy, City University of New York, New York, NY. 
email: Levi.Waldron@sph.cuny.edu

2. Ni Zhao, Department of Biostatistics, Johns Hopkins University, Baltimore, MD. 
email: nzhao10@jhu.edu

3. Ekaterina Smirnova (@katiasmirn), Department of Biostatistics, Virginia Commonwealth University, Richmond, VA. email: ekaterina.smirnova@vcuhealth.org

# Workshop Description

The composition of microbial species in a human body is essential for maintaining human health, and it is associated with a number of diseases including obesity, bowel inflammatory disease, and bacterial vaginosis.  Over the last decade, microbiome data analysis  almost entirely shifted towards using samples taken directly from various sites of human body and  to explore a  large number of microbes using 16S or whole metagenome sequencing. This technological shift has led to a radical change  in the data collected and led to the creation  of the  Human Microbiome Project (HMP) in 2008. With the growth and success of the microbiomics field, the size and complexity, and availability of the microbiome data in any given experiment have increased exponentially.  Publicly-available data sets from amplicon sequencing of two 16S ribosomal RNA variable regions, with extensive controlled-access participant data, provide a reference for ongoing microbiome studies. However, utilization of these data sets can be hindered by the complex bioinformatic steps required to access, import, decrypt, and merge the various components in formats suitable for ecological and statistical analysis. 

The main goal of this workshop is to provide a much-needed tutorial on downloading, understanding, and analyzing  the publicly-available HMP data. We will describe the two packages, HMP16SData and HMP2Data, that provide the comprehensive tutorial on the analysis of Phase 1 and 2 of the HMP project, respectively. These packages provide count data for both 16S ribosomal RNA variable regions, integrated with phylogeny, taxonomy, public participant data, and controlled participant data for authorized researchers, using standard integrative Bioconductor data objects.  As such, these packages provide the first comprehensive publicly-available tool for working with  microbiome data collected at different body sites (e.g., fecal, nasal, vaginal) coupled with other omics approaches (e.g., cytokines, whole metagenome), and is conducted longitudinally on multiple subjects at multiple visits. By removing bioinformatic hurdles of data access and management, HMP16SData and HMP2Data  enable researchers with only basic R skills to quickly analyze HMP data. This allows  studying the dynamics of microbial composition over the disease progression, discovering  disease-specific microbial biomarkers, and understanding the role of  microbiome in connection to other omics measurements.  

This workshop will consist of the series  on the instructors-led live demos presented together with  the brief lecture materials and statistical methods review when necessary. Completely worked out examples are available through the HMP16SData and HMP2Data package vignettes. 



## Pre-requisites

* Basic knowledge of R syntax
* Familiarity with the microbiome data 
* Familiarity with alpha and beta diversity in the context of microbiome data analysis
* Familiarity with principal components and principal coordinates analysis

Background reading:

* Schiffer L, Azhar R, Shepherd L, Ramos M, Geistlinger L, Huttenhower C, Dowd JB, Segata N, Waldron L (2019). "HMP16SData: Efficient Access to the Human Microbiome Project through Bioconductor." American Journal of Epidemiology. doi: 10.1093/aje/kwz006.



## Workshop Participation

Workshop participants are expected to bring a lap top, download HMP16SData and HMP2Data packages in advance, and be able to execute  R commands throughout workshop. 

## _R_ / _Bioconductor_ packages used

HMP16SData

HMP2Data

## Time outline 

| Activity                     | Time |
|------------------------------|------|
| HMP16SData                   | 10m  |
| HMP2Data                     | 10m  |
| Microbiome Analyses          | 15m  |
| Multi-omics data integration | 15m  |

# Workshop goals and objectives

The main purpose of this workshop is to help researchers interested in public microbiome data to start using  the HMP16SData and HMP2Data packages.  

## Learning goals

* understand the goals of  HMP projects and the studies available through the HMP DAC portal 
* download and use HMP data packages
* understand the difference between phase 1 and phase 2 projects
* understand principles of -omics data integration and visualization

## Learning objectives

* install HMP data packages and access vignettes
* download HMP data to produce analyses illustrated in package vignettes
* create sample summary statistics
* create alpha and beta diversity plots
* understand longitudinal patterns and examine microbiome diversity changes  
* integrate 16S and cytokines data using co-inertia analyses techniques 
* learn capturing patterns across -omics data sets of different structure