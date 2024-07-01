These files are used to generate the figures in the manuscript "Identifying Viable Financing Mechanisms for
Post-Earthquake Housing Reconstruction in Canada - Case Study of a M7 Earthquake in British Columbia". 

Additional post-processing in PowerPoint was used to generate the figures as seen in the paper. 

The OpenDRR damage and consequence files can be found here:
https://github.com/OpenDRR/earthquake-scenarios/blob/master/FINISHED/ACM7p0_GeorgiaStraitFault.md

The CSV files are outputs from the analyses that use the OpenDRR files above. They are read to create the figures.

The main file is a Jupyter Notebook used to run the analyses and generate figures.
If the conditional "if 1 > 2" is maintained, only the figures based on the CSV files will be generated.
If the conditional is changed (e.g., "if 10 > 2") then all analyses and figures will be recreated. The run time is much longer in this case.
