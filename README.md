PriPath: Identifying Affected  Pathways from Differential Gene Expression via Grouping, Scoring and Modeling with an Embedded Machine Learning Approach  


Malik Yousef 1, 2, Fatma Ozdemir3, 4, Amhar Jaaber3, Jens Allmer5, and Burcu Bakir-Gungor3

1 Department of Information Systems, Zefat Academic College, Zefat, 13206, Israel
2 Galilee Digital Health Research Center (GDH), Zefat Academic College, Israel
3 Department of Computer Engineering, Faculty of Engineering, Abdullah Gul University, Kayseri, Turkey
4University Institute of Digital Communication Systems, Ruhr-University,Germany
5 Medical Informatics and Bioinformatics, Institute for Measurement Engineering and Sensor Technology, Hochschule Ruhr West, University of Applied Sciences, Mülheim an der Ruhr, Germany

*	Correspondence: malik.yousef@gmail.com;


Abstract
Cell homeostasis relies on the concerted actions of several genes; and along this line, dysregulated genes lead to disease manifestations. In living organisms, genes, or their products, do not act alone, but instead act within a large network. Subsets of these networks can be viewed as modules which provide certain functionality for the organism. Kyoto Encyclopedia of Genes and Genomes (KEGG) systematically analyzes gene functions, genes and molecules, and provide a PATHWAY database. Measurements of gene expression (e.g., RNA-seq) can be mapped to KEGG pathways in order to determine which modules are affected in a disease. However, genes acting in multiple pathways, and some other inherent issues complicate such analyses. Current approaches neglect some of the existing knowledge which makes up the KEGG pathways. These approaches may only employ gene expression data to detect dysregulated pathways. However, approaches that take into account more of the compiled information are required for a more holistic association between gene expression and pathways. PriPath is a novel approach that transfers the generic approach of grouping, scoring followed by modeling (G-S-M) for the analysis of gene expression with KEGG pathways.
In our approach, we utilize the KEGG pathway as the grouping (term) information and insert this information into a machine learning algorithm for selecting the most significant groups (KEGG pathways). Those groups are utilized to train a machine learning model for the classification task. Our proposed approach successfully assigned KEGG terms to differentially regulated genes with medical relevance. We have tested PriPath on 13 gene expression datasets of various cancers and other diseases. We then compared the performance of PriPath with SVM-RCE, CogNet, and maTE, which are similar in their merit. The results indicate that we outperform maTE in most cases; and PriPath uses less number of genes than SVM-RCE-R and CogNet. For each dataset we manually confirmed the top results in literature and compared PriPath predictions to the predictions of Reactome and DAVID. 
PriPath can thus aid determining dysregulated pathways, which is applicable to medical diagnostics. In the future, we aim to advance the approach such that it will be possible to perform patient stratification based on gene expression and druggable targets. Thereby, we cover two aspects of precision medicine. 
