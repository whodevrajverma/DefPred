# DefPred: In-Silico Tool for Predicting, Scanning, and Designing Defensins

**DefPred** is a comprehensive computational platform dedicated to the identification, analysis, and design of **defensins**. Defensins are a major family of antimicrobial peptides (AMPs) that serve as a critical component of the
innate immune system in plants, invertebrates, and vertebrates. This tool addresses the challenge of identifying novel defensins from large-scale genomic and proteomic data.

**Web Server:** https://webs.iiitd.edu.in/raghava/defpred/


## Citation

Kaur D, Patiyal S, Arora C, Singh R, Lodhi G and Raghava GPS (2021) **In-Silico Tool for Predicting, Scanning, and Designing Defensins.**
Front. Immunol. 12:780610. https://doi.org/10.3389/fimmu.2021.780610

This dataset is available on Zenodo at

## About the Research

Defensins are small, cysteine-rich cationic peptides that exhibit broad-spectrum activity against bacteria, fungi, and viruses. They are characterized by a unique structural fold stabilized by three or four disulfide bonds.
DefPred provides a robust framework to classify these peptides and understand their functional properties.

* **Dataset:** The models were developed using a large dataset of **854 experimentally validated defensins** and **854 non-defensin peptides** (randomly selected from UniProt).
* **Methodology:** The platform utilizes several machine learning techniques, including Support Vector Machine (SVM), Random Forest, and Extra Trees, based on various sequence-derived features.


## Key Features

### 1. Robust Predictive Models

* **Sequence Features:** Predictions are based on amino acid composition, dipeptide composition, and physicochemical properties.
* **Evolutionary Information:** Uses **Position-Specific Scoring Matrices (PSSM)** to capture conserved evolutionary patterns unique to defensins.
* **Performance:** The best-performing model achieved a maximum **AUROC of 0.98** and an accuracy of 94.26% on an independent dataset.

### 2. Scanning and Designing Modules

* **Genome Scanning:** Allows researchers to scan entire protein or genome sequences to identify potential defensin-like regions.
* **In-Silico Design:** A module for generating peptide analogs. Users can introduce "point mutations" to observe how changes in the sequence affect the predicted defensin score and physicochemical properties.

### 3. Integrated Web-Bench

* **Comprehensive Search:** Facility to browse and search the dataset for known defensins based on source organism, peptide length, and disulfide connectivity.
* **BLAST Search:** Similarity search tool against the database of validated defensin sequences.
* **Physicochemical Profiling:** Calculates essential parameters like charge, hydrophobicity, and amphipathicity for submitted sequences.


## Applications

* **Antimicrobial Discovery:** Identifying novel defensins as candidates for next-generation antibiotics to combat multi-drug resistant pathogens.
* **Immunology Research:** Studying the evolutionary conservation and functional diversity of the innate immune response across different species.
* **Peptide Engineering:** Optimizing defensin-based scaffolds for better stability and lower toxicity in therapeutic applications.

## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.

## Support

The development of DefPred was supported by the **Department of Biotechnology (DBT)** and the **Council of Scientific and Industrial Research (CSIR)**, Government of India. Infrastructure and facilities were provided by **IIIT-Delhi**.
