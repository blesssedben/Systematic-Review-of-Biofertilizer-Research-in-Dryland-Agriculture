# Systematic-Review-of-Biofertilizer-Research-in-Dryland-Agriculture
This repository contains all datasets, screening records, supplementary tables and figures, and VOSviewer Pajek files used on Gephi for modularity analysis for the review article “Systematic Review of Biofertilizer Research in Dryland Agriculture.” 
The supplemnetary files ensure full transparency and reproducibility of the bibliometric workflow conducted in Scopus and Dimensions, including search queries, screening steps, cleaned datasets, and network analyses.
All analyses were performed between December 2024 and August 2025.

Software and Versions
VOSviewer v1.6.x

Gephi v0.10.x
All parameters and thresholds are described in Pajek network files


Reproduction Workflow

Search replication
Run the Scopus and Dimensions queries using the advanced search interface (the search strings are provided in the main text).
Export full metadata (CSV) for “Article” and “Review” types, language = English.

Screening and cleaning
View inclusion/exclusion criteria in the main text.
The final cleaned dataset is attached.

Network generation

Upload cleaned data into VOSviewer application and generate the network maps.

Run keywords co-occurrence, co-authorship, and citation network at three thresholds n ≥ 1, 3, and 5 for all network levels.
Export pajek files from VOSviewer to Gephi to run the modularity analysis.
Use default settings on Gaphi: resolution = 1.0; normalization = association strength; attraction = 2, repulsion = –1 (default).
