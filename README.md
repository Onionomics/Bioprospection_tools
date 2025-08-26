This space contains experimental natural language processing tools to discover natural products from related literature

# Bioprospection Tools

This repository contains a set of Python tools for the analysis of scientific literature focused on **metabolite bioprospecting**.  
The code allows processing *abstracts* exported from Scopus, PubMed, and WoS, identifying chemical compounds, and performing frequency analysis and visualization.

## Required external data

To run the analysis properly, you need four external datasets that are not included in this repository due to size/license restrictions.  

1. **MetaboCards**  
   - File: `metabocards.txt`  
   - Download from Google Drive: [MetaboCards](https://drive.google.com/file/d/1K8R7vkxSrd0d7i1oyBHBTSpz436uh9P7/view?usp=sharing)  
   - Location: place the file inside the `data/` folder of the repository.  

2. **ChEBI Lite**  
   - File: `ChEBI_lite.sdf`  
   - Download from Google Drive: [ChEBI Lite](https://drive.google.com/file/d/1F0IyY090tAXVZ2noRZaJvT__9BZvlwCd/view?usp=sharing)  
   - Location: place the file inside the `data/` folder of the repository.
  
3. **NPASS v1**  
   - File: `NPASSv1.txt` 
   - Location: into `data/` folder.  

4. **Scopus type export file**  
   - File: `compilated_search_results.csv` (or similar, generated directly from Scopus when exporting your search results). 
   - This file must be obtained directly by the user from Scopus and placed in the `data/` folder.  

⚠️ **Note:** Before running any notebooks or scripts, make sure the four files are available in the `data/` directory. The repository is configured to read them from there.


