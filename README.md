# Purtis_Master_thesis_codes

## Description of the Data Management Files:

1. **`N.Data_cleaning` and `N.more_variables`**
   - **Purpose:** Contains data cleaning codes necessary for creating the treatment, control, and outcome variables.
   - **Datasets Used:** SOEP datasets including `pl`, `ppathl`, `pgen`, and `hbrutto` (All in SPSS formats).
   - **Note:** `N.more_variables` must be run before `N.Data_cleaning`, as the latter depends on the output file generated by the former.
   - **Outputs:** The output files `N.2012_ONLY` and `N.covariates` will be generated in CSV formats and will be used in the sections ahead.

## Data Section (Graphs):

3. **`Graphs_data_` and `Graphs_data_appendix`**
   - **Purpose:** Contains the codes for generating graphs used in the data section and the appendices.
   - **Dependencies:** Utilizes the output files from the data management files and SOEP datasets including `pl`, `ppathl`, and `hbrutto` (All in SPSS formats).

## Analysis Files:

5. **`N.Longitudinal_CATE_estimates` and `N.Not_Longitudinal_CATE_estimates`**
   - **Purpose:** Contains the codes for estimating Conditional Average Treatment Effects (CATE) for the years 2013-2020, based on both longitudinal and non-longitudinal data. For testing statistical significance, plotting the results along with calculation and plotting confidence intervals
   - **Results:** The results from these files are presented in the Analysis section of the thesis.
   - **Dependencies:** Uses the output files from the data management files.

6. **`N.Separate_Subgroup_Analyses`**
   - **Purpose:** Contains the codes for analyzing variations in CATE estimates across different subgroups.
   - **Results:** The results are presented in the Analysis section and the appendix.
   - **Dependencies:** Uses the output files from the data management files.

7. **`N.Subgroup_Interactions_andmore`**
   - **Purpose:** Contains the codes for generating tables, graphs, and results based on interactions among different subgroups.
   - **Results:** The results are presented in the Analysis section and the appendix.
   - **Dependencies:** Uses the output files from the data management files.
  
8. **`N.MW_Analysis`**
   - **Purpose:** Contains the codes for generating CATE estimates(men) and CATE Estimates(women), testing statistical significance and plotting the results.
   - **Results:** The results are presented in the Analysis section of the thesis.
   - **Dependencies:** Uses the output files from the data management files.

## Simulation Study Files:

9. **`N.SIMULATION_STUDY`**
   - **Purpose:** Contains codes for the simulation studies presented in the respective section of the thesis and in Appendix C.


   
