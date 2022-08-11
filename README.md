# informative_entry_sims
Code for simulating and visualizing informative entry in clinico-genomic cohorts for the paper "Elucidating analytic bias due to informative cohort entry in cancer clinico-genomic datasets".

Two Rstudio notebooks are provided:
1) perform_simulations.Rmd - Performs simulations as described in manuscript text. To run these in a reasonable length of time on an individual machine, recommend changing num_cohorts for each scenario to a much smaller number than the 100,000 used for our final analysis. This generates four output files, one for each scenario. Output files from our analysis are also provided for use with visualize_results.Rmd .

2) visualize_results.Rmd - Generates figures and text output for Word table based on results of perform_simulations.Rmd. To visualize without running simulations, you download the ZIPped .csv files from Github first.

