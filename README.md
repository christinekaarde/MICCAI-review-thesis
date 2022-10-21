# Value-Analysis-Thesis

This repo contains the data and code for processing MICCAI papers from 2012 and 2021, creating an initial database of basic meta data, expanding with categorising articles as classification and other, mining the articles references and processing the data, generating graphs and qualitative outputs for further processing based on data gathered through manual annotation. 

This is used in my master thesis, "Exploring the landscape of MICCAI papers" from the IT-University of Copenhagen

## Data
The data used is partially mined from the Springer database hosting the proceedings, the proceedings articles themselves and data I gathered through manaul annotation of the articles.

## Combining proceedings txt 
takes the individual txt files from proceedings parts and joins it together

## Mining initial data 
uses html files from the Springer database hosting the proceedings to mine basic meta data

## Database creation and references 
adds categories to articles and mines the references for analysis (also included)

## Analysis 
contains code for creating graphs/qualitative analysis of collected manually annotated data. Part of this code is based off the code from the acl repo: https://github.com/coastalcph/acl-citations

With thanks given for the work done! Everything that I have borrowed is acknowledged in the notebooks, with comments outlining where I have changed anything. 

## Archive 
contains remnants of code cut from existing files and old versions of collected data (nothing used in the final thesis, but nice to have just in case)
