# MoEPaper
This paper includes all scripts involved with generating training, test, and validation datasets for our MoE Paper.

#Information About Scripts
- "citation_extraction.R" pulls all papers from PubMedCentral with abstracts that match inputted MeSH terms and timeframe
- "clean_datasets.py" takes datasets generated from "citation_extraction.R" and converts it into a format that includes specific information regarding each paper's abstract, year, the papers it cites, and the papers it is cited by
