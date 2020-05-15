[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3827500.svg)](https://doi.org/10.5281/zenodo.3827500)

This repository includes data and analysis to accompany the manuscript:

# Characterization of a thermally tolerant *Orbicella faveolata* reef in Abaco, The Bahamas

**Authors:** Katherine E Parker, Jeremy O Ward, Erin M Eggleston, Evan Fedorov, John Everett Parkinson, Craig P Dahlgren, Ross Cunning  
**Journal:** *Coral Reefs*  
**Link:** https://doi.org/10.1007/s00338-020-01948-0

---

This work analyses the abiotic and biotic factors contributing to higher thermal tolerance documented at Mermaid Reef in comparison to the neighboring less heat tolerant Sandy Cay Reef in Abaco, Bahamas. Temperature, depth, light intensity, and coral composition were analyzed, as well as host genotype diversity, Symbiodiniaceae composition, and bacterial communities in *O. faveolata* colonies at each site. This repository contains all analyses of environmental variables and Symbiodiniaceae composition. Microbiome data and code is available at [https://github.com/eme47/CoralMicrobiome](https://github.com/eme47/CoralMicrobiome).

---
**Repository contents:**  
  
**Data:**  

* **Data/sample_data.xlsx:** Metadata for coral samples, including site and depth

* **Data/qPCR/:** Raw qPCR data for Symbiodiniaceae quantification

* **Data/site_data/:** Coral reef benthic community composition and colony size from AGRRA surveys at both sites

    + **coral_composition_species.csv:** Coral reef benthic community composition from AGRRA surveys  
    + **coral_size.xlsx:** Summary statistics of *O. faveolata* colony sizes from AGRRA surveys
    + **mermaid_hobo.csv:** Temperature data from HOBO logger at Mermaid Reef
    + **sandy_cay_hobo.csv:** Temperature data from HOBO logger at Sandy Cay Reef
    + **MR_SC_light_data.xlsx:** Light data from HOBO loggers at both sites  
    
  
**Rmd:** 

* **Rmd/site_chacterization.Rmd:** Code to import and analyze temperature, light intensity, benthic community composition, and colony size for both sites 

* **Rmd/symbiont_qPCR_analysis.Rmd:** Code to import qPCR data and analyze Symbiodiniaceae composition 

