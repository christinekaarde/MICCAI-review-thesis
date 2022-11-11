# MICCAI-Review-Thesis

This repo contains the data and code for processing MICCAI papers from 2012 and 2021, creating an initial database of basic meta data, expanding with categorising articles as classification and other, mining the articles references and processing the data, generating graphs and qualitative outputs for further processing based on data gathered through manual annotation. 

This is used in my master thesis, "Exploring the landscape of MICCAI papers" from the IT-University of Copenhagen

## Data
The data used is partially mined from the Springer database hosting the proceedings, the proceedings articles themselves and data I gathered through manual annotation of the articles.

## Naming conventions
The folders in this repo are numbered in accordance with the work flow used in my thesis. Notebooks within folders have a similar structure, so 04-analysis is the final folder, containing 3 notebooks to be worked through sequentially: 04.01_name, 04.02_name and 04.03_name

## 01 Combining proceedings txt
takes the individual txt files from proceedings parts and joins it together
(used for mining the references and creating categories)

## 02  Mining initial data 
uses html files from the Springer database hosting the proceedings to mine basic meta data: title, authors, page numbers, DOI, year of publication and part of publication

## 03 Database creation and references 
03.01_defining-categories notebook adds categories to articles based on the titles and abstracts mined from the combined proceedings txt files from 01. Categories are based on keywords and rules and a threshold for information found
03.02_references-mining-and-analysis mines the references also from the combined proceedings txt and analyses the findings. This work borrows from the ACL repo: https://github.com/coastalcph/acl-citations
Comments have been added where I have altered the original code, with thanks given for the work done!

## 04 Analysis 
04.01_quantitative-analysis takes the data from my manual annotation of classification articles and creates graphs for numerical data collected
04.02_qualitative-analysis-part-1 looks at the text based answers in my annotations data, here I have manually collected more data, contained in the 3 csv files: affiliations_data, disease_data and justification_data
04.03_qualitative-analysis-part-2 uses these three csv files and looks for insights in the data

## 00 Archive 
contains remnants of code cut from existing files and old versions of collected data (nothing used in the final thesis, but nice to have just in case)


