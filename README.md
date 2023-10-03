# persian-poems-Search-engine

In this repository, Elasticearch is implemented on a collection of Persian poems collected by a team of Sharif University students from ganjoor.ir.   

In order to compare the effectiveness of existing pre-processing libraries for the Persian language, data pre-processing has been done using the two famous libraries of Hazm (https://github.com/roshan-research/hazm) and Parsivar (https://github.com/ICTRC/Parsivar).
 The files contain the following content:
• SE1.ipynb: A search engine without any pre-processing (----)
• SE4.ipynb: Perform pre-processing using Hazm (with Lemmatization and removing stop words) (NTRL)
• SE4'.ipynb: perform pre-processing using Parsivar (with Lemmatization and removing stop words) (NTRL)
• SE4''.ipynb: performing pre-processing using Hazm (with Stemming and removing stop words) (NTRS)

The report file compares the pre-processing methods in terms of Precision, Recall, F-measure, and MAP.
