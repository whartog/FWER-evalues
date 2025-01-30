# FWER-evalues
Data and code for "Family-wise Error Rate Control with E-values"

The file e_values_vonf.Rmd is the simulations for Section 5.2, producing the file Ts_data_holm.csv

The file factorial_design.Rmd is the simulations for Section 5.3, producing the files Ts_data.csv and Ts_data_1.5.csv, which are the data with primary budget, and Ts_data_equal_budget.csv and Ts_data_equal_budget_1.5.csv, which are the data with equal budget. I decided later to include mu=1.5 as well, so I had to do those simulations and create a new file for each sim.

All these five files are used in the e-dag data analysis.Rmd file, in which the computations and plots are done and explained.
