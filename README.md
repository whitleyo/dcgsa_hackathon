# DCGSA Hackathon

This competition is meant as a learning exercise for life sciences trainees at the Donnelly Centre who want to learn how coding can be applied to biological problems.

## The challenge: 

based on gene expression, protein protein interaction information, and (optionally) any external data you might find, predict which genes are 'core essential' genes identified in Hart et al. 2015 (https://doi.org/10.1016/j.cell.2015.11.015) CRISPR screens.

## The data:

The data provided is as follows:

* __data/train.csv__: combination of expression data for cancer cell lines as well as protein protein interaction data from the IntAct database (https://www.ebi.ac.uk/intact/), as well as a binary identifier (1 for yes, 0 for no) denoting whether or not the given gene is one of the core essential genes identified in Hart et al. 2015 (https://doi.org/10.1016/j.cell.2015.11.015). Expression data corresponds to that publication as well.

* __data/test.csv__: data in same format as data/train.csv, but to be used for testing.

## Example:

an example analysis has been provided in the scripts directory
