# SLE777-Group-Assignment
This project is part of the SLE777 assignment 4 at Deakin University.

#### -- Project Status: [Active]

## Project Overview and Objectives

The main aim of this project is to assist collaborators in understanding and analysing biological data more effectively.

Part 1 focuses on the analysis of gene expression data in TSV format. This section will include visualizations to facilitate insights into the frequency of gene expression. Additionally, we will filter and analyze Tree Circumference data collected over 20 years to uncover differences across various tree sites.

Part 2 involves a comparative analysis of gene sequences, nucleotide frequencies, and amino acid biases between E. coli and C. baratii. This part will also highlight comparisons between the two organisms, employing data visualizations to support our findings and conclusions.

### Methods Used
* Statistics
* Data Visualisation

### Technologies
* R 
* R studio

### Libraries Required
* 'Seqinr'
* 'ggplot2'
* 'R.utils'


## Contributing Members
* Elvin 
* Simon 
* Bhargavi

## Contact
We can be contacted via our deakin university emails

## Project Contents
In this repository, you will find two reports named "Part_x_Report", each highlighting a different part of our project. Alongside these, there is a respective R notebook that includes all the code we used, "Part x Code". The reports provide a detailed overview of our findings and share the strategies we employed to solve the problems, along with the necessary code to reproduce our results.

### "Part 1 Code"
This file will contain all of the code required for 2 main tasks, firstly gene expression where we read a gene expression file, form a table and filter the genes with a mean expression lower than 10. We also plot the mean expression to get a gauge on the distribution. 
Secondly, we analyse the tree growth data from 2005 to 2020, measuring tree circumference between two different sites, "northeast" and "southwest". We calculate the mean and standard deviations then assess changes between the start and end, as well as the growth in the final 10 years. A t-test is run on the growth in the last 10 years, to see any differences between the sites. 
### "Part_1_Report"
This file contains all of the code from the "Part 1 Code" file, however some things may be ommited for the report to make it clearer. The data and findings are also analysed and interpreted within this R markdown file. 
This file is knitted into a html file for ease of sharing.
### "Part 2 Code"
This file will contain all of the code required for analysing  DNA nucleotide usage, Sequence length, Codon biases and k-mer representation between E. coli and C. baratii. This is all done similarly with "Part 1 Code", it is all standalone and can be run in the single file to do all of the analysis.
### "Part_2_Report"
This file contains all of the code from the "Part 2 Code" file, however some things may be ommited for the report to make it clearer. The data and findings are analysed and interpreted within this R markdown file.
This file is knitted into a html file for ease of sharing.
## How to use our code and data
Please install any of the packages required and initialise the libraries, this can be done within the code notebooks, or the reports.
The report and code is designed to run in isolation without requiring input from the user, hit the "run all" if data is not downloaded, or "run below" below the downloading chunks to begin. 

## Future Work
* Potential extensions of the analysis
* Adding new datasets to gain deeper insights





