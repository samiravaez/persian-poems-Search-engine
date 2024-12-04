# Persian-Poems-Search-Engine

In this repository, Elasticearch is implemented on a collection of Persian poems collected by a team of Sharif University students from ganjoor.ir.   

In order to compare the effectiveness of existing pre-processing libraries for the Persian language, data pre-processing has been done using the two famous libraries of Hazm (https://github.com/roshan-research/hazm) and Parsivar (https://github.com/ICTRC/Parsivar).  

 The files contain the following content:  
 
• SE1.ipynb: A search engine without any pre-processing (----)  

• SE4.ipynb: Pre-processing using Hazm (with Lemmatization and removing stop words) (NTRL)  

• SE4'.ipynb: Pre-processing using Parsivar (with Lemmatization and removing stop words) (NTRL)  

• SE4''.ipynb: Pre-processing using Hazm (with Stemming and removing stop words) (NTRS)  

The report file compares the impact of pre-processing methods on the system in terms of Precision, Recall, F-measure, and MAP.
