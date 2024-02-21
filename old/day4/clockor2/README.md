# Molecular clock tutorial  

## Description of sequence data  
Set of simulated rabies virus whole genome sequences (n=60). They should be related to the Africa-2 clade, which has previously been found in Nigeria. The clock rate is ~3 to 5x10-4 depending which root fitting method is applied. 

## Metadata  
The metadata is also fabricated, including simulated dates. Location data is at the state level and there should be a degree of phylogeographic clustering apparent. There are a few versions of the data:  
*nig-af2-seqs-metadata.txt*: represents the "raw" Metadata  
*nig-af2-seqs-clockor2.csv*: this is the data formatted for clockor2 (tip, date, group headings). This contains a deliberate error to showcase an outlier on the root to tip plot, sample 16 has the wrong date (is 1999 instead of 2019).  
*nig-af2-seqs-clockor2-corrected.csv*: the above with the outlier date corrected (after checking raw data)  

## Tree
Newick tree generated from FastTree using a GTR model
