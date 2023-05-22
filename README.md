# MetaCommunityStability_Chain
Meta-community dynamics in a chain network to analyze how upstream species affect downstream stability in gut microbiota.

The codes here are used in the study by Shibasaki and Mitri (2023). These codes are used to generate meta-community simulations, perform analyses, and drow some figures. For the easy replication of the results, codes are summarized in jupyter notebooks (Notebook_SSSM2022 for simulations, and StatAnalysis for data analysis, respectively).

You can also find the csv files that contain the data used in the above study.
The simulation files exist in the three folders named ./connectance_xxx, where xxx repleresnts the connectance of iteraspecific itneraction networks (xxx = 0.25, 0.50, or 1.00).  These three folders are compressed in"data.zip." For each connectance, we generated 20 me-tacommunities, and analyzed two scenarios, assembly and designing (see the manuscript for the definition) over two migration parameters rho and mu.

For manipulation of species itneraction, see folder ./Manipulation ./Manipulaiton2, and ./Manipulation3. The data of Psuedo-spatial is provided in ./Psuedo_Spatial
The notebook also explains other minor files.
