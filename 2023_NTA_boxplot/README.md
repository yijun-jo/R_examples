# 2023-R_boxplot-barplot_long-wide-data-tidying-example
This is an example of coding in R to create boxplots and barplots with some data tidying by switching a wide dataset to a long dataset.

# 1. Sample source
Samples were collected during an extracellular vesicle purification process. 
TFF Input: conditioned medium from YZ3 transfected U2OS cells that was cleared of cells by centrifugation and larger debris by normal filtration by 0.45um and 0.22um filters. 
TFF Permeate: permeate from tangential flow filtration by a 700kDa MWCO at TMP of 30psi and shear rate of 8000/s.
TFF Retentate: retentate from tangential flow filtration by a 700kDa MWCO at TMP of 30psi and shear rate of 8000/s.
CC700 Input: resuspended pellets from PEG precipitation of TFF retentate.
CC700 FT: flow-through of EV from Capto Core 700 chromatography.

# 2. Data source
The particle concentration and sizing data were collected on ZETA particle sizing instruments. 
    File for particle concentration data: yijun_conc_graph_new.csv
    File for sizing data: yijun_size_graph_.csv

The volume data was manually recorded during the purification process.

# 3. How to use the files?
All code and output results/graphy were included in the .html file.
Raw data were in the .csv files.
