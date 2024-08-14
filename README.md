# F1L-ComBio-2024

# Intro 
This repository will contain my progress throughout the Pharma/biotech internship emulator with Dean Lee. The weekly updates will contain my thoughts, questions, and codes as I dive deeper into learning about scRNA-seq analysis in the context of cancer therapy and drug discovery. 

# Week 1
Developing an effective and safe drug treatment for cancer therapy requires multiple validation steps using computational modeling systems, cell lines, animal models, and patient-derived xenografts before the human subject clinical trials. I want to use the online scRNA-seq data to explore the therapeutic benefits of following FDA-approved drugs for other cancer types. 

Trastuzumab, targeting HER2: essentially binding to the HER2 protein and blocking the downstream signaling pathways that lead to cancer growth. HER2 is present in more aggressive breast cancer, therefor Trastuzumab has been used as a single agent or combined with other drugs like Doxorubicin hydrochloride, cyclophosphamide, and either paclitaxel or docetaxel; or Docetaxel and carboplatin.

as an FDA-approved drug, trastuzumab is also effective in Stomach adenocarcinoma combined with cisplatin and either capecitabine or fluorouracil in patients whose cancer is HER2+. all together they interfere with the cancer proliferative program and destroy cancerous cells. 

Bevacizumab, targeting VEGF: This drug targets the supply mechanism for the cancer cells by targeting the protein involved in the development of the vascular system needed to feed the cancer cells. This target protein is called vascular endothelial growth factor (VEGF) and is essential for most of the solid tumor growth. 

VEGF angiogenic effects are mediated by VEGF-1 and VEGF-2 receptor tyrosine kinases. lymphomagenesis, inducing placental growth factor, and induction of BCL2 expression to prevent apoptosis in endothelial cells are examples of other VEGF molecular and cellular functions. 

breaking the KSQ:

are cell lines a good model to start choosing which cancer types would respond to the drugs? 
cancer cell lines are modified cells taken from patients with different cancers that can replicate in the appropriate cell culture environment. These models can be used as the first line of testing drug toxicity but don't necessarily represent all the physiological aspects of the disease. moreover, considering the unstable genetic nature of cancer, cancer cell lines would accumulate genetic mutations and alterations after several passages that would make it hard to conclude in the field. Further validation steps should be conducted in xenograft and PDX models. 

what does sqRNA seq tell us and what it has different from bulk RNAseq?
Bulk RNA sequencing only captures an "average" of the expression profiles from thousands of cells, whereas single-cell RNA sequencing (scRNA-seq) allows for individual measurements across dozens to thousands of single cells.





references: 
https://www.cancer.gov/about-cancer/treatment/drugs/trastuzumab
https://www.enhertuhcp.com/en/breast/efficacy/enhertu-clinical-study-destiny-breast-03?utm_source=Bing&utm_medium=cpc&utm_term=her2%20breast%20cancer%20info&utm_campaign=Enhertu%20HCP%20Unbranded%20Her2%20Treatment_Unbranded_Diagnosis_PH&gclid=04c2f375fa921f06973795c9e02b42bf&gclsrc=3p.ds&msclkid=04c2f375fa921f06973795c9e02b42bf
https://www.nature.com/articles/nm0603-669


