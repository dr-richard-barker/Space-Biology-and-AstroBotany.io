![NASA_GeneLab_banner](https://dr-richard-barker.github.io/Space_Biology_and_AstroBotany.io/Images/NASA_GeneLab_banner_v3_scroll_down.jpg "NASA_GeneLab_banner")
## Space-Biology-and-AstroBotany.io

Preliminary analysis reveals some NASA Data files produced by the GeneLab analysis team that should be easy to open, combine and visualise. 

This Google CoLab notebook above pulls data from the GeneLab API.

[https://github.com/dr-richard-barker/Space-Biology-and-AstroBotany.io/OSDR_API_demo_viewing_OSD-37.ipynb](https://github.com/dr-richard-barker/Space-Biology-and-AstroBotany.io/blob/main/OSDR_API_demo_GLDS-37.ipynb)

---



**Simple challenges and short-term goals to help enable analysis** 


![GeneLab_gadgetIcon](https://dr-richard-barker.github.io/Space_Biology_and_AstroBotany.io/Images/GeneLab_gadgetIcon.png "NASA_GeneLab_Computer")

---

**Metadata summary**

Is there a simple way to sort and summarize the meta-data? 

Is there a way to quantify the similarity of the accessions based on their metadata?


**Multi-Omics data**

Is there a way to merge normalized counts for heatmaps?

Is there a way to merge counts for statistical analysis? 

Is there a way to merge multi-omics data?

---

## What is the best way to present data and share insightful methods?

![GeneLab_mitochondrial_stress](https://dr-richard-barker.github.io/Space_Biology_and_AstroBotany.io/Images/DRB_2022_K_transporters_in_space_miriocondira_oxidatiive_phosphorylation.png "GeneLab_mitochondrial_stress")

This prototype figure was made for artistic merit, it uses data projected onto a KEGG pathway that was then customised using Adobe Photoshop to aid with narrative development related to changes in membrane transport.
There are several scientifically relevant data presentation issues with this figure, primarily there isn't a color scale, showing that red is up and blue is down in gene expression. 
This figure has some blurry text and can't evolve further highlighting how the use of "notebook-embedded" data visualisation synthesis has long-term advantages. 

---
## Plan of action 

So here's the preliminary plan for what our Colab notebook will look like with the goal of exploring genetics data:

**1. Setting Up the Stage:**

Import Necessary Libraries: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn (depending on the analysis goal this may vary).
Mount Google Drive: Accessing my datasets stored there.
Download Required Data: Specifying URLs or using cloud storage options.
Data Preprocessing: Reading files, handling missing values, formatting genotypes/phenotypes.
Quality Control: Checking for outliers, ensuring correct sample IDs, exploring data distributions.


**2. Exploration and Visualization:**

Descriptive Statistics: Summarizing genotypes and phenotypes, identifying interesting patterns.
Principal Component Analysis (PCA): Visualizing relationships between samples based on genetic variation.
Clustering: Grouping samples based on similarity, potentially revealing subpopulations.
Genome-Wide Association Studies (GWAS): Identifying potential genetic variants associated with traits.
Visualization of Results: Creating informative plots and heatmaps to showcase findings.


**3. Advanced Analysis (Optional):**

Network Analysis: Exploring interactions between genes and pathways.
Machine Learning: Predicting phenotypes based on genotypes or identifying subgroups.
Differential Expression Analysis: Identifying genes with different expression levels between groups.
Functional Annotation: Linking genetic variants to known biological functions.


**4. Sharing and Collaborating:**

Saving and Exporting Results: Keeping organized outputs for further analysis or presentation.
Sharing the Notebook: Collaborating with colleagues and making research reproducible.
Documenting Code and Findings: Clear comments and annotations for understanding the workflow.


**5. Adapting the Notebook:**

Depending on the specific research question and data type, adjustments will be made:
Choosing appropriate analysis methods and tools.
Tailoring visualizations and interpretations to the context.
Integrating additional libraries or workflows for specific needs.


** Please consider co-developing this Google CoLab notebook, it is currently designed just to pull data from a Plant SpaceFlight experiment from the GOpen Science Data Archive (OSDA).**

[https://github.com/dr-richard-barker/Space-Biology-and-AstroBotany.io/SDR_API_demo_viewing_html_files_in_notebook.ipynb](https://github.com/dr-richard-barker/Space-Biology-and-AstroBotany.io/blob/main/OSDR_API_demo.ipynb)


---

# **Example questions that we should be able to ask of expression data**


A. Is there a simple way to plot the normalised counts as a heat map?

B. Can the .html and other results files be viewed in the CoLab notebook?

C. Is there a way to view the differential expression data on Reactome pathways?

D. Is there a way to perform Geneset enrichment analysis of differentially expressed loci? 

E. Is there a way to perform PCA, K-means and T-SNE clustering to identify functionally related co-expression clusters? 


--_


**Early Goal:** This test website was created to practice methods of presenting data analysis methods using the github repo.
Ultimately the Space Biology and AstroBotany.io repo has the goal of making space biology data more FAIR and providing useful material for intergrating Data from NASA Open Science Data Archive into future statistical analysis. 
