**PriPath: Identifying Affected  Pathways from Differential Gene Expression via Grouping, Scoring and Modeling with an Embedded Machine Learning Approach**  
Link to the paper :  https://www.researchsquare.com/article/rs-1449467/latest.pdf
<br>
See this [page](https://github.com/malikyousef/PriPath/blob/main/pages/SettingsKnime.md) for information about setting Knime.
<br>
Visit this [page](https://github.com/malikyousef/PriPath/blob/main/pages/TableFormat.md) for instruction in how to prepare the dataset into Knime table format (*.table) using a Knime workflow
<br>
Visit this [page] for the outputs of PriPath.
<br> 
The Knime workflow name is "PriPath_Sep_2022.knwf" that you might download and run throug the Knime platform

## The main workflow is: ##

**Running the workflow:**

- You need to use the node “MCCV Iterations” in order to specify the number of Monte Carlo Cross Validation (MCCV) iterations, for example 10 or 100.
- You need to configure the node “List Files/Folders” to point it to the folder that has the gene expression dataset in a table format (as described above).

![alt text](https://github.com/malikyousef/PriPath/blob/main/images/PriPath_main.PNG?raw=true)


 
 ## The content of the MetaNode PriPath is : ##
 
![alt text](https://github.com/malikyousef/PriPath/blob/main/images/PripPath_MetaNode.JPG?raw=true)

 ## The content of the G-S-M component ##
 
 ![alt text](https://github.com/malikyousef/PriPath/blob/main/images/Ttest_and_GSM.JPG?raw=true)

## The 3 main component of G-S-M ##
 ![alt text](https://github.com/malikyousef/PriPath/blob/main/images/G-S-M_all_steps.JPG?raw=true)
