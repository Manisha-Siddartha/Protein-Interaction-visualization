# Protein-Interaction-visualization
TTU CS5331 Project 3: Data Visualization Weekly Report

1st week:

Work by Vidya Eswarappa:

went through http://www.cbioportal.org/ and made a study with cancer topics and its cause.
Brief idea on using the data from the cbioportal using specfic ids like cancer_type id.
Work by Manisha Nalla:

Went through sample visualisation code.
Idea on implementation of Network Visualisation(protien study).
work by venkatesh:

worked on API.
Retrieval of dynamic data for further process.
week 2:

work by vidya:

using API retrieved data to diagonsis of age for a particular cancer.
work by Manisha:

Research on protiens that increment and decrement the rate of cancer
work by venkatesh:

Implementation of network visualisation for over all protiens apart from 140 protiens.
Week 3:

work by vidya

worked on adjacency matrix to form a relationship between proteins of same cancer.
work by Manisha and Venkatesh

Worked on Data retrieval part for protiens related to one type of cancer.

Network Visualization For Dynamic Data From Cbioportal :

Please click to watch the overview video.

video

Project By : 1. Venkatesh Papineni 2. Manisha Siddartha Nalla 3. Vidya Eswarappa 4. Sree Hari Inukollu Texas Tech University - Department of Computer Science on 12/12/2016 with reference to the course Project 3 of CS5331-004: Visualization and Visual Analytics course. This project is based on network visualisation to view and retrieve the data from cbioportal.

Highlights of features implemented in this project: Researched on the cbioportal website on data useful to make a better network visualisation and design a web application.Initially worked on retrieving the dynamic data from cbioportal using the web api. eg: webservice.do?cmd=getCaseLists&cancer_study_id=gbm_tcga.

Project summary: This project concentrates on taking a sample set of protiens and visualising them to show in what percentage different combination of protiens affect occurances of various cancers. As the visualisation of all the cancers becomes clumsier we concentrated on displaying only 10 cancer studies.In addition the amount of people affected by those cancers in various age groups has been shown.

ScreenShot of entire project: main screenshot.

Able to retrieve the mutated genes for a particular cancer type and implemented the relation between the mutated gene of a particular cancer with other mutated gene of different cancer using the adjacency matrix with x and y axis to be mutated genes of a cancer types that occur in all cancer type.The cancers contribute to the arms of rose chart. +


When clicked on the rose_chart of particular cancer type we are able to show the diagnosis of age on a bar graph of that cancer type. which plots the count of members under particular age that were affected by that cancer.


//Interesting findings:

There has been a few common most frequent persons in both the blogs. For instance, 'barack obama' is one of the the most frequent terms both the blogs talked about.
ScreenShot

There has been a few common most frequent miscellaneous topics in both the blogs.
ScreenShot

We observe that after 2008 the former US president grorge w. bush is not much talked in the blogs.
ScreenShot

During 2008 and 2012, US president barack obama is the most frequent term because of US elections during that years.
ScreenShot

The top 200 locations mentioned in both the news blogs are almost same. So, we can say that these two blogs mostly focus on locations of articles related to each other.
ScreenShot

ScreenShot//

Duties of each student in our group:

Below are the duties of each student in our group: Venkatesh:

Retrieved the cancer data for sample set of protiens.
Able to visualise the cancer data on rose chart.
Performed on click functionality from matrix cell to rose chart.
Involved in integration of different parts of project. write the left over parts here

Vidya Eswarappa:

Retrieved the data dynamically that was required for the diagnosis of the age.
Implementation of the bar graph to show the diagnosis of age.
Helped in the visualising the relations between the proteins.

Manisha nalla

Have implemented the protiens matrix.
Highlighting on cell highlights the entire axis.
Have displayed the rose charts in all the cells in matrix.
have helped vidya in visualising the ages on barchart.
Helped venkatesh in the integration.

sree hari:

Software required for the implementation of this Project

The following are the Software that we have used to create this visualization:

Sublime Text editor. It can be downloaded from here.

D3.js. It can be downloaded from here.

live-server. Instructions to setup are available here.

Node.js. It is required for set up of live-server. It can be downloaded from here.

Steps to run

Place all the relevant files in the same folder.

Start the live-server using live-server command.

Select the project html file (index.html file in this case).

Our web application link

To view our web application of Text and Geospatial visualization of texts extracted from news/blogs, please click here.

Acknowledgments

This is project has been implemented by Venkatesh Papineni, Manisha Siddartha Nalla, Vidya Eswarappa, Sree Hari Inukollu under the esteemed guidance of professor Tommy Dang at Texas Tech University.
