# service-robustness

[![DOI](https://zenodo.org/badge/237173423.svg)](https://zenodo.org/badge/latestdoi/237173423)

Code to analyse the relationship between ecosystem service robustness to loss of species and our proposed network fragility metric. The analysis is conducted on simulations on the published [Web of Life](http://www.web-of-life.es) ecological networks of varying type. The associated research paper for this published as Samuel RP-J Ross, Jean-François Arnoldi, Michel Loreau, Cian D White, Jane C Stout, Andrew L Jackson, Ian Donohue. 2021. Universal scaling of robustness of ecosystem services to species loss. Nature Communications, 12(1) p5167. [doi](https://doi.org/10.1038/s41467-021-25507-5)

The analysis consists of a main file "empirical-networks-analysis.Rmd" that contains the various functions we define in the associated paper, alongside the code to apply it to the suite of empirical networks. The folder "data/" contains the original data as downloaded from the [Web of Life](http://www.web-of-life.es). The folder "images/" contains printed figures from the analysis. The folder "export/" is empty by default but the code can be edited to export csv copies of the data to this folder if required. This code is released with a GNU General Public License v3. The theory is developed in a Jupyter notebook that includes python code "robustness_theory.ipynb". 
