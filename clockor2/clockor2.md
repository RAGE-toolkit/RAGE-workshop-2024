# Using clockor2 to infer virus evolution

In this practical we will be use molecular clocks to analyse viral evolution in pre-constructed trees, test the fit of a clock and explore ways to root phylogenetic trees. 

## Task 1 - Preparation

Navigate to the folder clockor2 which contains a newick tree, fasta file and the respective seuqnce metadata.

On your browser, navigate to [Clockor2](clockor2.github.io)


## Task 2 - Upload files

Once on https://clockor2.github.io, drag and drop your newick file, or click `select file` to navigate to the file on your local computer. 

Upload your tree annotation file, which should be a csv file. Headers should be `tip,date,group`. An example file can be found [here](https://clockor2.github.io/MERS_dates.csv).
The group is the variable defining our monophyletic groups. This could be lineage, state, host etc. 

Click ` Parse csv`

Visually inspect your tree and associated output

## Task 3 - Analyse

1. Hover over the points on the graph. Do these correlate to where you expect the taxa to be located on the tree?

2. Now click on any taxa on the tree and see it highlighted on the graph. 

   Are there any sequences that look like outliers?

3. Note the evolution rate of the unrooted tree, and respectiveR-squared and RMS values. 

4. Root the global tree using both the R-squared and RMS values. 

5. Note the recalibrarted evolutionary rate of your tree, and the R-squared and RMS values. How do they compare to the unrooted values? 


Given these values, what is the best way to root this specific tree?



## Task 4 - Export

You can export your tree in different formats. Rectangular, circular etc


## Task 5 - Re-iterate with different trees of your data

You can also compare different trees of your data e.g., changing the group variable!


