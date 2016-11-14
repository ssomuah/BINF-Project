# BINF-Project

The main script is in project.R

hacks.R looks at ways of dealing with datsets that are non-binary in terms of disease and control.

datasetStats.txt is output by hacks.R and has information on all the datasets taken from the spreadsheet.

datasetStats-2.txt is the same format as datasetStats.txt but tries to transform the disease.states based on some known names for controls,
normal, control, healthy etc.


ids is just a list of dataset IDS taken from the spreadsheet




##TODO
*Differentiate between up and down regulated genes
*Print out intermediate steps, toptable per disease, genes per disease
*Figure out how to fix special case datasets
