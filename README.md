# preprocessing_raw_dbgap
Code for preprocessing raw data with dbgap attributes 
The sample dataset for this iteration is
Eric A. Collison 2014
Fresh-frozen lung adenocarcinoma specimens.
Method 1 to download files:
  - go to https://portal.gdc.cancer.gov/
  - look up TCGA-LUAD, select and create a cohort and name it.
  - go to repository, select open, transciptome profiling, gene expression quantification, and star-counts.
  - download.
Filter	                        Purpose in pipeline
Open	                          lets you analyze without access barriers
Transcriptome Profiling	        picks the RNA expression biology layer
Gene Expression Quantification	gives you numerical expression columns
STAR – Counts	                  enforces a consistent counting workflow so the matrix is valid.
Method 2 to download files:
rawfiles


Landi: Affymetrix Human Genome U133A Array (GPL96), Expression profiling by array"
Collison: Bulk RNA seq via Illumina HiSeq 2000 ,  expression profiling performed via RNA sequencing
<img width="952" height="907" alt="image" src="https://github.com/user-attachments/assets/a6161d71-d10c-4884-9931-692649a5e399" />
