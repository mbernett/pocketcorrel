# pocketcorrel
Material necessary to conduct pocket correlation analyses, namely Pocketron pocket cross-talk, Dynamic Network (DyNet) analysis, and Distance Fluctuation (DF) analyses, on MD trajectories. 
The three folders refer to three different systems, specifically the A2A receptor, the androgen receptor (AR), and the epidermal growth factor receptor (EGFR) kinase domain.
The Jupyter Notebook is intended for use with the data in the folders, which contain preprocessed data (analysis subfolder) to conduct the analysis through the Notebook and input files (md_inputs) to perform the MD simulations. 
The Notebook shows the analyses on the EGFR system, but can be straightforwardly adapted to the other two systems as well.

The environment with all the packages necessary to run the Jupyter Notebook can be created with: `conda env create -f environment.yml`


