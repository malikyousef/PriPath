**PriPath: Identifying Affected  Pathways from Differential Gene Expression via Grouping, Scoring and Modeling with an Embedded Machine Learning Approach**<br>
Malik Yousef<sup>1,2</sup> ,Fatma Ozdemir<sup>3, 4</sup>, Amhar Jaber<sup>3</sup>, Jens Allmer<sup>5</sup>, and Burcu Bakir-Gungor<sup>3</sup><br>
<sup>1</sup> Department of Information Systems, Zefat Academic College, Zefat, 13206, Israel<br>
<sup>2</sup> Galilee Digital Health Research Center (GDH), Zefat Academic College, Israel<br>
<sup>3</sup> Department of Computer Engineering, Faculty of Engineering, Abdullah Gul University, Kayseri, Turkey<br>
<sup>4</sup>University Institute of Digital Communication Systems, Ruhr-University, Germany<br>
<sup>5</sup> Medical Informatics and Bioinformatics, Institute for Measurement Engineering and Sensor Technology, Hochschule Ruhr West, University of Applied Sciences, Mülheim an der Ruhr, Germany<br>

*	Correspondence: malik.yousef@gmail.com;

Link to the paper :  https://www.researchsquare.com/article/rs-1449467/latest.pdf
<br>
## Knime ##
PriPath tool is a Knime workflow. In order to run the workflow, you need to download Knime and install it in your local machine.
This is the link for downloading Knime: https://www.knime.com/downloads<br>
For more information about the Knime platform you might visit https://www.knime.com/software-overview <br>
See this [page](pages/SettingsKnime.md) for information about setting Knime.
<br>
Visit this [page](https://github.com/malikyousef/PriPath/blob/main/pages/TableFormat.md) for instruction in how to prepare the dataset into Knime table format (*.table) using a Knime workflow
<br>
Visit this [page](https://github.com/malikyousef/PriPath/blob/main/pages/GroupingFile.md) for instruction in how to upload the Groups file.  
Visit this [page](https://github.com/malikyousef/PriPath/blob/main/pages/outputs.md) for the outputs of PriPath.
<br> 
The Knime workflow name is "PriPath_Sep_2022.knwf" that you might [download](PriPath_Sep_2022.knwf) and run throug the [Knime](https://www.knime.com/)platform

## PriPath main workflow is: ##

**Running the workflow:**

- You need to use the node “MCCV Iterations” in order to specify the number of Monte Carlo Cross Validation (MCCV) iterations, for example 10 or 100.
- You need to configure the node “List Files/Folders” to point it to the folder that has the gene expression dataset in a table format (as described above)
- You might [download](GDS4824.table) an example of such data named [DSD84.table](GDS4824.table)

![alt text](https://github.com/malikyousef/PriPath/blob/main/images/PriPath_main.PNG?raw=true)


 
 ## The content of the MetaNode PriPath is : ##
 
![alt text](https://github.com/malikyousef/PriPath/blob/main/images/PripPath_MetaNode.JPG?raw=true)

 ## The content of the G-S-M component ##
 
 ![alt text](https://github.com/malikyousef/PriPath/blob/main/images/Ttest_and_GSM.JPG?raw=true)

## The 3 main component of G-S-M ##
 ![alt text](https://github.com/malikyousef/PriPath/blob/main/images/G-S-M_all_steps.JPG?raw=true)
