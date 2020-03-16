# IBDomics


How to use the code:

In python 3 or higher
IBDomics: ranking genes of interest on network with incremental random walk with restart and disease module cohesion
1) run incremental_rwr.ipynb  ro run multiple random walks on a chosen network. 
2) run merging_tables.ipynb to combine incremental rwr to a single rwr matrix
3) run full_incremental_rwr_evaluation_pipeline.ipynb to filter rank and annotate the incremental rwr matrix (this should be done in a jupyter notebook)
4) run disease_module_cohesion_ranking.ipynb for disease module cohesion ranking (this should be done in a jupyter notebook)
