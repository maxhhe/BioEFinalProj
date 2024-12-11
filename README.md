# BioEFinalProj

This README will provide a step by step walk through of how to set up an instance of JBrowse2 to visualize the difference in genomes of specific Coronavirus taxons. 

You will need to already have downloaded Node.js, wget, samtools, apache2, and tabix.

To download and set up JBrowse2, follow the steps in this provided documentation: https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpz1.1120 

Follow the data loading instructions with these links: 
  
  SARS Cov2: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/009/858/895/GCF_009858895.2_ASM985889v3/ 
  
  Human Coronavirus Oc43: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/003/972/325/GCF_003972325.1_ASM397232v1/
  
  MERS: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/000/901/155/GCF_000901155.1_ViralProj183710/ 

Replace the config.json file in your JBrowse2 folder with the provided one in this repo in order to set up the default view. 

You will now be able to open your localhost browser and visualise the genomes using JBrowse2.
