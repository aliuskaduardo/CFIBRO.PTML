# CFIBRO.PTML
CFIBRO.PTML General Data Protection Regulation (GDPR) compliant AI data analysis, management, 
and synthetic data generation and data protection for Cystic Fibrosis patients from basque country.

# Authors
Carmen Velásquez 1, Estefania Asencio-Medina 1,2,3,4, Amaia González-Magaña1, 
Maria D. Pastor-Vivero1,5, Laura Acosta3, Aliuska Duardo-Sánchez6, 
Sonia Arrasate 7, Humberto González-Díaz1,7,8, David Albesa-Jové,1,7,8,*

# Affiliations
1 BIOFISIKA: Basque Center for Biophysics CSIC, University of The Basque Country (UPVEHU),    Barrio Sarriena s/n, 48940, Leioa, , Basque Country, Spain.
2 Department of Coatings and Polymeric Materials, North Dakota State University, Fargo, North Dakota 58102, United States.
3 CITIC-Research Center of Information and Communication Technologies, Department of Computer Science and Information Technologies, University of A Coruña (UDC), 15071, A Coruña, Spain.
4 IKERDATA S.L., ZITEK, University of The Basque Country (UPVEHU), Rectorate Building, 48940 Leioa, Spain.
5 Cruces University Hospital, IIS Biocruces-Bizkaia, 48903, Barakaldo, Basque Country, Spain.
6 Department of Public Law, University of the Basque Country UPV/EHU 48940, Leioa, Biscay, Spain.
7 Department of Organic and Inorganic Chemistry, Faculty of Science and Technology, University of The Basque Country (UPV/EHU), P.O. Box 644, 48080, Bilbao, Spain.
8 IKERBASQUE, Basque Foundation for Science, 48011, Bilbao, Spain.

# Abstract
Cystic fibrosis (CF) is an autosomal recessive monogenic disease caused by mutations in a gene on the long arm of chromosome 7 that codes for the CFTR (Cystic Fibrosis Transmembrane conductance Regulator) protein. These mutations cause dysfunctional transport of chloride and other ions such as sodium and bicarbonate (Fonseca et al., 2020) which leads to the generation of thick and viscous mucus secretions from the lungs, as a consequence the airways are obstructed with an ideal environment for microbial colonization. The main treatment in this disease and specifically in exacerbations (phenomenon where there is a rapid deterioration of lung function) is antibiotic therapy according to the antibiotic resistance profile obtained from clinical micribiology plate culture. However with this method is slow and not totally accurate. In this context, combining Next-generation sequencing (NGS) PCR-based metagenomics for the identification of bacterial species from a clinical sample combined with Artificial inteligence /Machine learning (AI/ML) could be a fast track solution to create customized Personalized Medicine (PM) treatments for specific patients. Here we used the  Information Fusion +Perturbation Theory + Machine Learning (IFPTML) data pre-processing technique combined to Linear and Non-linear ML methods like Linear Discriminant Analysis (LDA) and Artificial Neuronal Networks (ANN) to obtain a PM predictive model for CF patients. Last, GDPR compliance Synthetic Data (SD) generation experiments by Monte Carlo (MC) methods have been performed in order to avoid patient re-identification and test model robustness at the same time. 

# Personal Data Protection

All data management and analysis were in compliance with the General Data Protection Regulation (GDPR). GDPR defines pseudonymization in Article 4 (5) as: 'the processing of personal data in such a way that they can no longer be attributed to a data subject without the use of additional information, provided that such additional information is kept separately and is subject to technical and organizational measures intended to ensure that the personal data are not attributed to an identified or identifiable natural person'. In general terms, pseudonymization aims at protecting personal data by hiding the identity of individuals (data subjects) in a data set, for example by replacing one or more personal data identifiers with so-called pseudonyms and by adequately protecting the link between the pseudonyms and the initial identifiers. Consequently, all patient data was pseudonymized by the team of the Biocruces Foundation by using an internal code to identify the patients. These codes and the identities of patients were never shared with the other researchers in this paper or the public in general. 

# Supporting Information
Supporting information files contain the following information:

Supporting Information file SI00.doc
Under construction

Supporting Information file SI01.xlsx
Under construction

# ANN code
Supporting information file IFPTML-ANN-CFIBRO.c contain the code in c language of the ANN models trained and validated in this paper. The code of the software used to generate the models is part of the STATISTICA package an is not propietary of the authors for release. The code may be used to implement the model in other software ever following the licence specifications by Statsoft inc. specified inside these files. Please in case you want to obtain similar ANN models use this package or other ANN algorithms package implemented in Phyton, WEKA, or other algorithms. In any case, we would like to point out that the linear models presented in the paper are simpler and have similar to better statistical performance than the ANN models released here. If your objective is using our models to predict new fuel blends we recommend the linear models instead of the ANN models released here. This linear models can be run in Excel or in any other script using the linear equations presented in the paper. You can reproduce the models using the data released at follows in the Supporting information files.

# Funding
Eusko Jaurlaritza/Basque Goverment, Health Department.
Grant: PIDFQ, Ref. FBB-PID-FQ, 2022-2023, Funds: 30965.0 Eur 

# References
Under construction


