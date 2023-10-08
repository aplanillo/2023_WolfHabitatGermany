# Planillo_etal2023_DivDist
 
This repository contains the R-scripts used in the analysis of wolf habitat suitabilty in Germany and the non-stationary habitat selection of the expanding population. 
Due to conservation concern, the original data is not provided. Data at a broader scale can be found in the _data_ folder.

In the _Rscripts_ folder there are eight scripts, two source scripts and six scripts for the analyses.
The scripts are prepared to be ran from the R project in the main folder.

The source scripts contain the R libraries and custom functions that are used in the other scripts. 
The scripts 01 to 06 contain the code for:
* data preparation (scripts 1 and 2)
* comparison of the different datasets and modelling algorithms (script 3)
* make a global ensemble model (script 4)
* test for non-stationarity by comparing the models from colonization steps to the global model (script 5)
* calculate expected number of wolf territories and analysis of reproduction in territories (script 6)

To run the scripts, data should be provided with the proper coordinates or the code should be adapted to work with the environmental values already provided in the tables in _data_ folder.
