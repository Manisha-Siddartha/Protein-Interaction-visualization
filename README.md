# Protein-Interaction-visualization
TTU CS5331 Project 3: Data Visualization Weekly Report

Click on this link to view the working prototype. 

http://myweb.ttu.edu/vpapinen/

Please click to watch the overview video.

video


Project By :

1. Venkatesh Papineni 
2. Manisha Siddartha Nalla 
3. Vidya Eswarappa 
4. Sree Hari Inukollu 

Project summary: This project concentrates on taking a sample set of protiens and visualising them to show in what percentage different combination of protiens affect occurances of various cancers. As the visualisation of all the cancers becomes clumsier we concentrated on displaying only 10 cancer studies.In addition the amount of people affected by those cancers in various age groups has been shown.

ScreenShot of entire project:

![ScreenShot]()


to retrieve the mutated genes for a particular cancer type and implemented the relation between the mutated gene of a particular cancer with other mutated gene of different cancer using the adjacency matrix with x and y axis to be mutated genes of a cancer types that occur in all cancer type.The cancers contribute to the arms of rose chart. 

1. screenshot1:
![ScreenShot](https://github.com/venkatesh45/Protein-Interaction-visualization/blob/master/2016-12-10.png)

2. screenshot2:
![ScreenShot](https://github.com/venkatesh45/Protein-Interaction-visualization/blob/master/2016-12-10%20(1).png)


When you select a particular cell in the matrix, rose chart will be ploted with legands, labels and slider.
![ScreenShot](https://github.com/venkatesh45/Protein-Interaction-visualization/blob/master/DV-1.png)

When clicked on the rose_chart of particular cancer type we are able to show the diagnosis of age on a bar graph of that cancer type. which plots the count of members under particular age that were affected by that cancer.

![ScreenShot](https://github.com/venkatesh45/Protein-Interaction-visualization/blob/master/bar%20graph.png)

Each Student Paticipation:

Below are the duties of each student in our group:

Venkatesh:

1. Retrieved the cancer data for set of protiens.
2. Visualise the data on rose chart.
3. Performed on click functionality from matrix cell to rose chart.
4. Involved in integration of different parts of project. 
5. Dynamically displayed the rose charts in the matrix
6. Legands for Rose Chart
7. Slider for Rose Chart

Vidya Eswarappa:

1. Retrieved the data dynamically that was required for the diagnosis of the age.
2. Implementation of the bar graph to show the diagnosis of age.
3. Helped in the visualising the relations between the proteins.

Manisha nalla

1. Have implemented the protiens matrix.
2. Highlighting on cell highlights the entire axis.
3. Have displayed the rose charts in all the cells in matrix.
4. have helped vidya in visualising the ages on barchart.
5. Helped venkatesh in the integration.

sree hari:


Interesting findings:
 
Highlights of features implemented in this project:

Researched on the cbioportal website on data useful to make a better network visualisation and design a web application.Initially worked on retrieving the dynamic data from cbioportal using the web api. eg: webservice.do?cmd=getCaseLists&cancer_study_id=gbm_tcga.

