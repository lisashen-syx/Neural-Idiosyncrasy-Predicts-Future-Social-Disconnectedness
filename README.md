# Neural-Idiosyncrasy-Predicts-Future-Social-Disconnectedness

The manuscript is currently under review. To comply with the guidelines outlined in the Journal’s Code and Software Submission Checklist, a small, simulated dataset (with individual-level data for 10 participants and dyad-level intersubject neural similarity in 5 brain regions for 45 unique dyads) is provided in the demo code. 

R version 4.3.1 on a Mac OS Sonoma 14.4.1 was used to write and run the source code. On a 2021 MacBook M1 Pro with 16GB of RAM, it takes about 1 minute to run through the code with this simulated dataset.

To run the source code, please first change the filepath to your local path of the downloaded demo_code folder. You can run each block of code in demo_code.Rmd individually or all the blocks by clicking on the "Run" menu and selecting "Run All" from the dropdown menu.

The source code produces the following result dataframes: results_isc_indeg_min,
results_isc_indeg_min_contr, results_isc_perceived_min, and results_isc_perceived_min_contr, corresponding to the main analyses predicting dyadic minimum of Time 2 indegree centrality or perceived popularity using Time 1 intersubject neural similarity outlined in our manuscript (with _contr denotes the additional analyses conducted when controlling for Time 1 dyadic minimum of indegree centrality or perceived popularity). They are analogous to the output generated for the results reported in our manuscript, except that they are based on the simulated dataset, such that none of the results based on the simulated dataset were statistically significant.
