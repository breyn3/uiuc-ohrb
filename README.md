
Study title: Flux, Impact, and Fate of Halogenated Xenobiotic Compounds in the Gut  
----------------------------------------------------------------------------------  

Authors: Atashgahi S, Shetty SA, Smidt H and de Vos WM  
Correspondence: WMdV (willem.devos[at]wur.nl)  
For code related queries: SAS (sudarshan.shetty[at]wur.nl) 

This repository contains codes for analysis done in the review article by Atashgahi S., et al (2018) Flux, impact and fate of halogenated xenobiotic compounds in the gut.  _Front. Physiol. - Gastrointestinal Sciences_. [Link](https://www.frontiersin.org/articles/10.3389/fphys.2018.00888/abstract).  

Structure:  
Atashgahi-et-al.-XenobioticReview2018  
project folder:
```
Structure:  
Atashgahi-et-al.-XenobioticReview2018/
|------- Genomes/    # contains list of genomes used for analysis.    
          |------- "genome_results_EC_hits.txt" # file with hits for genes searched in IMG/ER.  
          |------- "genomecart_export.txt" # List of genomes used. Upload to IMG/ER as genome cart.  
          |------- "genome_taxonomy.txt" # Metadata on genomes used here.  
          |------- "dehalo_genes.tab" # list of selected genes searched in IMG for the selected genomes. Upload this in function cart.
                        
|------- Human_gut_metagenomes/ # contains list of human gut metagenomes.  
          |------- "metagenomes_EC_counts_254.txt" # file with hits for genes searched in IMG/ER.
          |------- "metagenomes_export_254.txt" # List of human gut genomes used. Upload to IMG/ER as genome cart.
          
|------- Figure 4 XXXXXXXXXXXX.Rmd # RMarkdown file with stepwise codes to generate figure 4.
|------- IMG_Search.Rproj # The Rproject file.  
|------- Supplemantary_code_Figure_4_XXXXXXXXXXX_2018.pdf # RMarkdown file knited as pdf.  

```
Clone or download the repository as zipped file, unzip and open the .rmd file in R to re-run the analysis. 
