# TRGN510_final-project-outline
## Title: Comparison of kidney cancer gene expression for white female patients age from 20-60 versus African American female patients age from 20-60
## Author: 
- Tingman Zhu (Eva) 
## Contact: 
- tingmanz@usc.edu
## Overview of project: 
- RNA-Seq is a powerful tool for analyzing gene expression profiling. It can effectively detect the expressed genes between different conditions over the genome-wide level. For my project, I am interested in comparing differences in kidney cancer gene expression between white female patients age from 20-60 versus African American female patients age from 20-60. I would use the Bioconductor to analyze the RNA-seq in the HT-seq counts file. And this is the vignette I would use https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html

## Data
- White female patient(16 samples from TCGA database on the [GDC Data Portal](https://portal.gdc.cancer.gov/):
  - f426d6b8-5010-471c-aa9c-253269f6bc03.htseq.counts.gz
  - 426b94fe-fcff-49f2-9d0b-c7cb49bb5559.htseq.counts.gz
  - a7d05ea6-aa28-457f-a20b-57e812b614e1.htseq.counts.gz
  - 1d443e1f-794b-45bb-ae6f-91f57d5fca33.htseq.counts.gz
  - df0b7118-2a68-420e-a1dd-236e05bc8fe8.htseq.counts.gz
  - 984ea13e-adc6-48f7-830d-66ce450a2ea0.htseq.counts.gz
  - d7e7ad52-ecde-4744-b4e7-28dea4d186da.htseq.counts.gz
  - 60547e35-d42f-44bd-a9e8-21d57da93ee8.htseq.counts.gz
  - fddf0083-59bd-4352-8e3d-7e5715f6d5b0.htseq.counts.gz
  - 7a790ece-2c1a-4895-a475-9fabbc0622a3.htseq.counts.gz
  - 3dce2e68-bcf1-42b6-9374-b2724a0f5242.htseq.counts.gz
  - 2950c137-45e0-458f-987f-31de7f7befc4.htseq.counts.gz	
  - 5c9f1a05-1dc7-4e83-8dc2-3e5071796c07.htseq.counts.gz
  - 34e77fac-9e4b-481c-9a6c-a1b5f0916f06.htseq.counts.gz
  - bed7e30b-bf94-41d1-80f6-0595ff21bd3e.htseq.counts.gz
  - f3876e31-2267-458d-826f-769bcfb34e56.htseq.counts.gz
  
- African American patient(16 samples from TCGA database on the [GDC Data Portal](https://portal.gdc.cancer.gov/):
  - 26dcc91b-b7d5-47c1-8135-e5ab4f4e4be5.htseq.counts.gz
  - a8ecb5d8-ece5-43cc-843c-da81dc031ced.htseq.counts.gz
  - e1c82878-ac01-45bd-83b0-4bc606039670.htseq.counts.gz
  - 8d39e856-f93f-4eab-90ef-1e924b059fee.htseq.counts.gz
  - 405e401d-d3fc-468c-8c63-c8dddf9b3ee3.htseq.counts.gz
  - 20cdc1be-7412-4457-ab53-90dcfdf26f93.htseq.counts.gz
  - 89528cea-b21b-4ea8-a271-3d3f3ff142c9.htseq.counts.gz
  - 29e88863-d1b0-4da0-be95-d0a82eb1d08b.htseq.counts.gz
  - b2842754-010e-4f64-905d-89ef3eab3dc9.htseq.counts.gz
  - 596e3dbd-9928-4800-8026-6d1cfb9f5a57.htseq.counts.gz
  - 93e77514-c77b-4346-ae63-3e0d10512cff.htseq.counts.gz
  - f00b69a3-c3d2-4499-b337-abbce3e48f9b.htseq.counts.gz
  - ab461441-1f45-4ae5-b5da-ebb58817f75c.htseq.counts.gz
  - 84400ad5-cd37-4a94-a143-5c470599d1ce.htseq.counts.gz
  - 2147de22-3a52-490d-a4f6-32f6637ca24f.htseq.counts.gz
  - a8d90f96-19e8-4b2c-a9c8-904a4063d235.htseq.counts.gz

## Milestone 1:
- I would download the files from the National Cancer Institute GDC Data Portal website and load these data to R. Then I will set up limma, glimma and edgeR library in my RStudio. I would also check the format of my files and make sure the data can be transformed from raw data to usable data and can be processed by Bioconductor. Furthermore, I would calculate some values such as cpm, lcpm, mean and median. 
   - **Updats status 11/3/2020**: This milestone target has been accomplished
## Milestone 2:
- I would analyze the data effectively and understand more about RNA-seq. I would display or draw some plots such as heatmaps (show expression level), MDS plot (an informative representation of the similarities and dissimilarities in a sample) and some boxplots to better analyze my data. 
   - **Updats status 11/3/2020**: This milestone is ongoing

## Deliverable：
- R markdown
