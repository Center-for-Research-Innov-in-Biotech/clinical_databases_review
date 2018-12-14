# clinical_databases_review
Figures and analysis code provided for the manuscript:
"Assessing the public landscape of pharmaceuticals with evidence of clinical testing"

## data
Contains data outside of the CDEK database that were used to generate figures.

## figures
Contains the raw code, output data, and png for figures generated and published in the manuscript. The file "data_links.csv" is outputted from the "fig3_API_overlap_between_sources" jupyter notebook and contains the following information:
1. api_id (unique id given to an active pharmaceutical ingredient in our database. There may be many rows for a given api_id if the active pharmaceutical ingredient is found in many databases. Search the prefered name at cdek.wustl.edu to find more information on the active pharmaceutical ingredient.)
2. source_api_id (unique id from the source listed in "source_name". This field can be used to cross-reference data sources)
3. api_name (selected preferred name for the active pharmaceutical ingredient, usually the generic name)
4. source_name (Can be one of the following: 
* [ChEMBL](https://www.ebi.ac.uk/chembl)
* [DrugBank](https://www.drugbank.ca)
* [PubChem](https://pubchem.ncbi.nlm.nih.gov)
* [nme](http://cribdb.wustl.edu)
* [WITHDRAWN](http://cheminfo.charite.de/withdrawn)
* [repoDB](http://apps.chiragjpgroup.org/repoDB)
* [superdrug2](http://cheminfo.charite.de/superdrug2)
* [Drug Central](http://drugcentral.org)