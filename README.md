This space contains experimental natural language processing tools to discover natural products from related literature

# Bioprospection Tools

This repository contains a set of Python tools for the analysis of scientific literature focused on **metabolite bioprospecting**.  
The code allows processing *abstracts* exported from Scopus, PubMed, and WoS, identifying chemical compounds, and performing frequency analysis and visualization.

## Required Data

To run the pipeline, place the following files inside the `data/` folder:

1. **ChEBI_lite.sdf**  
   Chemical Entities of Biological Interest (ChEBI) database.

2. **NPASSv1.txt**  
   Natural Product Activity and Species Source database for biomedical research.  

3. **Metabocards.txt**  
   Chemical ontology database from the Human Metabolome DataBase (HMDB).

