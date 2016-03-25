## Project Info
 - Organization: Canadian Center for Computational Genomics (C3G)
 - Project title: Development of an HTML dynamic matrix to represent datasets with multiple dimensions
 - Project Proposal Markdown Version: [https://github.com/Madhuka/d3-visualization-html/blob/master/project-profile/markdown-version.md](https://github.com/Madhuka/d3-visualization-html/blob/master/project-profile/markdown-version.md)

 - URL of project idea page: [https://bitbucket.org/mugqic/gsoc2016#markdown-header-development-of-an-html-dynamic-matrix-to-represent-datasets-with-multiple-dimensions](https://bitbucket.org/mugqic/gsoc2016#markdown-header-development-of-an-html-dynamic-matrix-to-represent-datasets-with-multiple-dimensions)

## Project Abstract
Canadian Center for Computational Genomics (C3G) provides bioinformatics analysis and HPC services for the life science research community. They have completed more than 400 bioinformatics analysis projects. The Montreal C3G nodes are hosted at the McGill University and Genome Quebec Innovation Center (MUGQIC). The Montreal node is strongly involved in the GenAP development team and had developped a robust genomic data analysis pipeline set.  GSOC project is to development a HTML dynamic matrix to represent datasets with multiple dimensions.

The International Human Epigenome Consortium (IHEC) Data Portal can be used to view, search and download the data already released by multiple member consortia. The International Human Epigenome Consortium (IHEC)[2] Data Portal centralizes epigenomics datasets coming from different IHEC-associated projects, by storing the relevant metadata in a relational database system. 

Most real-world datasets have numerous dimensions mainly in bioinformatics. Beyond choosing a more complex visual representation the standard solution to this problem is to only visualize a subset of the dataset dimensions. User needs to get these extra dimensions for analysis task.  Multidimensional process groups data into two categories in two dimensional view. To navigate  easily through available datasets with multiple dimensions and enable items selection, DIG Viewer [3] has been developed, as an open-source library creating versatile HTML grids. The grid of DIGViewer allow users to navigate through datasets, using multiple metadata dimensions. DIGViewer is used to display epigenomics experiment results as it has multiple dimensions that are collected from multiple sources [4]. As such, all available datasets are displayed by cell types in rows, as said in columns.

Still it contains some limitations such as expanding and collapsing rows / columns in matrix, freezing title of the matrix while scrolling, updating grid content as data model update, filtering functions for the rows and columns, selecting partial cell content in the grid, row-based grouping brackets, exporting grid to files, important standard csv file to the grid view, querying values in row and columns and search for data in the view. The proposed solution would be an answer to all these issues.

## Biographical Information
### Student Profile
I am G P D Madhuka Udantha, an MSc by Research student at the Department of Computer Science and Engineering, University of Moratuwa. Currently I'm working as a research assistant at the LK Domain Registry affiliated with the University of Moratuwa. My research is about clustering web session and pattern mining. My research is sited with big data and, modeling user access patterns, visualization techniques with pattern mining. I have experiences in data matrix in multiple dimensions in web usage mining for my master research which is most similar to this project.

I graduated from the Faculty of IT, University of Moratuwa in 2011 with first class. During my undergraduate period I was involved in many software projects including a GPS/GSM based fleet management system (group project), Offline email System (final year individual project) etc.  After graduation I worked as a senior software engineer at WSO2 Lanka Pvt Ltd the opensource middleware company for nearly 3 years prior to pursuing a research career. I gathered great experience in working in opensource culture at WSO2 and gained exposure in using and developing Apache projects such as Axis2, Synapse and Tomcat. I also have a solid development background with javascript, java, j2me, OSGi, REST and web services while mainly contributing to WSO2 User Engagement Server which main graphical interface and the dashboard of the WSO2 product stack. I am main contribute jaggery, which is opensource and server side script framework. I was a speaker on wso2 con, 2014 on tutorial of ‘Javascript Everywhere: Backend to Web and Mobile Apps in Javascript I have solid background for visualization, UX and JavaScript. I have completed GSOC 2015 successfully apache project (COMDEV-119 Zeppelin GSoC Project: add more D3 visualization [6])

I'm delighted to apply for the Montreal C3G nodes, this year as a GSOC student as I'm very interested to do project on developing the HTML dynamic matrix to represent datasets with multiple dimensions and contributing to the community.

## Contact Information
 - Email : madhukaudantha@gmail.com
 - Phone number:  +94774066336
 - Address: 505/3A, Work Camp Road, Dalupatha, Negombo, Sri Lanka.  
 - IRC nick: Udantha
 - Skype Id: madhukaudantha
 - Linkedin : https://lk.linkedin.com/in/madhukaudantha
 - Blog : https://madhukaudantha.blogspot.com
 - Github :  https://github.com/Madhuka
 - Contribution for open source:
 - https://github.com/wso2/jaggery/graphs/contributors
 - https://github.com/Madhuka/apache-zeppelin-gsoc

## Student Affiliation 
 - Institution: University of Moratuwa, Sri Lanka
 - Program: Master in Science
 - Stage of completion: Near to end of this year
 - Address: University of Moratuwa, Bandaranayake Mawatha, Katubedda, Moratuwa 10400, Sri lanka.

## Schedule Conflicts
Availability for the Summer Project
I'm a full-time research student working on my research area big data and visualization techniques with pattern mining and I will be available during the whole summer for the proposed project. The work I'm involved in at LK Domain Registry is 100% aligned with my research; therefore I will not have any conflicts during the period.  

## Mentors
 - Mentor names: David Bujold
 - Mentor emails: david.bujold@computationalgenomics.ca
 - Mentor link_ids: https://bitbucket.org/dbujold/
 - Have you been in touch with the mentors? Yes, From March 11 over emails (18 email thread)

## Synopsis
### Aims of the project
Add new advance navigational features for DIG Viewer for smooth negation that leads to improved data analysis process over  multidimensional dataset such as epigenomics experiment results in DIG Viewer.

### Details
According to project markdown documentation [5] DIG view are limited with some functionalities that decline smoother navigation. Those limitations make data analysis process hard as navigation is not smoother for large multi dimensions datasets. To solve this I am introducing few components which are responsible for each feature and it will help code maintenance also. These components are reusable so those can be used in later additional features as well. Expanding collapsing UI components are used for rows and columns. Freezing title to visible matrix title while scrolling, data binding to the model so data model and grid is update, filtering function can be used for row and columns and to select partial cell in grid. There are some simple improvements such as row-based grouping brackets and exporting current view of the grid to CSV. D3 js library can be used in all the places.

## Benefits to Community
C3G makes available comprehensive sets of reference epigenomes relevant to health and disease. DIG Viewer which has been developed using D3 js library allows users to navigate on multiple dimensions, epigenomics experiment results. Human participation plays an essential role in most decisions when analyzing data. Lot of data is now multi-dimensional but there are lack of tool provide visualization an better navigation on those type of data. The proposed project involves improving the DIG Viewer visualization and functionalities which provide smoother and effective navigation in multiple dimensions.

DIG viewer is used to analysis epigenomics experiment results and it makes easy and smooth navigation and it will help data analysis process. This can be used in other projects in C3G also.

This also can be used to visualize multidimensional database (MDB) data and lead to get better navigational queries. In statistical engineer, scientist, researcher and econometrics also can used this to analysis their multidimensional data set [8,9]. It is extremely useful in cancer genomics projects and DIG viewer let them to make their finding easy n fast [10]. Community will get considerable befits. 

## Coding Plan & Methods
### Introduction 
C3G makes available comprehensive sets of reference epigenomes relevant to health and disease. DIG Viewer which has been developed using D3 js library allows users to navigate on multiple dimensions, epigenomics experiment results. The proposed project involves improving the library visualization and functionalities which provide smoother and effective navigation in multiple dimensions.

According to project markdown documentation [5] DIG view are limited with some functionalities that decline smoother navigation. Those limitations make data analysis process hard as navigation is not smoother for large multi dimensions datasets.
Listed features improve the library to provide smoother navigation.

#### Main required features

1.	Expanding/Collapsing rows and columns in matrix with transitions
2.	Making matrix rows and columns always visible while scrolling vertically or horizontally
3.	Updating grid content using transitions when data model gets updated
4.	Rows/columns display filtering based on provided function
5.	Partial cell content selection

#### Other improvements

6.	Row-based grouping brackets 
7.	Exporting current view of the grid to CSV 

#### Few more Proposing features

8.	Query the dataset rather than showing full dataset in  view
9.	Search data in matrix grid
10.	Import csv file to grid view

To solve this I am introducing few components which are responsible for each feature and it will help code maintenance also. These components are reusable so those can be used in later additional features as well. 
Below section explains all the proposed features descriptively with some design.

#### Expanding and Collapsing feature rows or columns
 - Items are grouped by categories (top level hierarchy) and it let grid present datasets in compact view.
 - The grid does not need to display everything at all time. Depending on the user’s requirements, user can get more detailed view with rows or columns expanding feature.
 - Example IHEC Data Portal grid doesn't display all cell type under a cell type category. The category would be expandable by clicking on the ‘+’ sign next to it if it is collapsed. A ‘-‘ sign would allow the row/column to be collapsed again.
 - This is offered as an option by grid API.
 - There will be Expanding All / Collapsing All function also as user can get full view of grid with one click of 'expand all' and compact view with 'collapse all'
 - D3's transitions will used to give smooth visual transition expanding and collapsing feature.

#### Making matrix rows and columns always visible when scrolling vertically or horizontally
 - Currently in DIG viewer user needs to scroll UP or left in order to see matrix rows and columns
 - matrix rows and columns titles are freeze when user navigating in data grid scrolling vertically or horizontally

#### Updating grid content when data model gets updated
 - Current grid does not show when data model get change.
 - Whenever the data model has update that modification need to present in the grid accordingly with smooth D3's transitions
 - This change should not harm the current state of DIG viewer

#### Filtering function for rows and columns display 
 - User is able to provide a filtering function which only displays the matrix rows/columns
 - This not  harm  the data model and it is only viewing data in grid
 - Removal and insertion of rows and columns will use D3 transitions 
 
#### Partial cell content selection
 - User can select or deselect cell or cells in the grid
 - This feature presents a dataset of selected portions of the datasets represented by a cell
 - The popup will contain a table of available datasets with a selection widget
 - Columns in this dataset table will be provided by injected functions provided by the user of the API
 - Table can be sortable and selecting table row  highlights the mapping cell with changing the cell color

#### Other small improvements

#####	Row-based grouping brackets 
 - Rows can be grouped with bracket and once bracket is clicked all rows will get selected in that brackets

#####	Exporting visible rows and columns in the grid to CSV files
 - User can do above features such as filtering and collapse rows or columns then user export only showing grid to csv file
 - User can select file types such as (CSV or TSV)
 
#### Few more proposed features
#####	Query the dataset rather than showing full data set in the view
 - User can  query the data before loading the data to grid 
 - Only interested data can be picked in initial stage but not filtered
 
#####	Search data in matrix grid
 - Grid view show only rows and columns but user need some dimensional data which is not shown in grid view (where cell is not selected)
 - Users can search dataset and results are presented as changing the color of the cells 

#####	Import csv file to grid view
 - As the gird can export its data to csv file, the same way user can load his / her csv file to the grid

Above contains all the improvements that are listed and I noticed to have in DIG viewer.

### 	Goal and Objectives
The Goal of this project is to enhance the navigational features for DIG Viewer for smooth negation that leads to improved data analysis process over multidimensional.

#### 	Objectives
 - High level study of DIG Viewer and multiple dimensions data navigation methods. 
 - In depth knowledge on data visualization techniques and with navigational mechanism over multiple dimensions visualization.    
 - Research more depth into D3 js feature which are needed for above features.
 - A good design and methodology to include new features
 - Come up with a good, user friendly UI component  for DIG viewer 
 - Designing and Implementing the features
 - Do Usability tests and collect feedback from other developers and the community
 - Document the implementation details and use cases
 - Test new features with sample epigenomics experiment results
 - Write user documentation
 - Extensive community interaction and gaining sufficient support from the C3G community.

## 	Timeline

March 26 to April 22 (Before the accepted proposals are announced) 
 - Try out DIG View and going through the C3G and Montreal C3G nodes documentation and getting a holistic idea on the project's functionality and user cases
 - Familiarize myself with D3 visualization into more depth and follow grid API in DIG viewer.
 - Study multidimensional visualization, interaction and navigation mechanism into more deeply and update findings over the community and team.
 - Learn D3 specification deeply and identify d3 features that will be used fully for project needs
 - Read papers and resources related to multiple dimensions  data visualization techniques and analytics UI tools
 - Go through the DIG Viewer to get hands on experience on the code base
 - Further discuss with developers regarding the approach I'm proposing about features 
 - Write blog posts and articles on stuff that I learn

Apr 23– May 23 (Community Bonding Period)
 - Discuss the features and use-case for each feature
 - Discuss the Mockups – UI for proposed features and finalize the diagram
 - Picking d3 features that is mapping in to our needs according to the feature list  
 - Understand data model and grid of DIG viewer
 - Discuss  on the improvements features 
 - Discuss and finalize high level use-case for each feature
 - Finalizing feature designs  
 - Discuss  about the architecture of the system and select coding pattern and design patterns for implementing
 - Have a skeleton component structure for features ready in mind and in agreement with the mentor

##### 	May-23 Coding starts

May 23 - June 05
 - Start developing new  feature expanding and collapsing rows and columns in matrix
 - Adding user interface elements for expanding and collapsing
 - Implementing a mechanism to selecting  items to be grouped by categories 
 - Improve the grid API
 - Adding D3 transitions for matrix when expanding and collapsing

June 06 - June 12
 - Adding row-based grouping brackets which small improvement 
 - Adding select function for grouping brackets
 - Adding D3 freezing title for grid matrix
 - Document the newly added feature

June 13 - June 21
 - Improve matrix rows and columns always visible with freezing / lock feature
 - Adding scrolling vertically or horizontally feature for grid content
 - Adding filtering function for rows and columns

June 20 - June 26
 - Binding the grid matrix view with filtering feature
 - Removal / insertion of rows and columns to the grid 
 - completing the D3 transitions for all added features
 - Code review with the mentor
 - Submitting details for midterm

##### 	2015-June-27: Midterm evaluations

June 27 – July 3
 - Sharing status of implementation with community and getting feedbacks
 - Improve the code depending on the feedback
 - Data model binding to grid feature developing
 - Adding  d3 event listener for data model update 

July 4 – July 17
 - Improving DIG Viewer display element to update with data model update event 
 - Start developing partial cell content selection feature
 - Update current code for new feature regard partial cell selecting
 - Adding popup table with mapped datasets with a selection cells
 - Improving the table for sorting and mapping to grid 

July 18 – July 24
 - Function get current visible cells data and meta data
 - Exporting data which is in current view of the grid to CSV and TSV with D3
 - Importing feature also implementing
 - Overall task review and adjustments
 - Document the development steps

July 25 – July 31
 - Adding query feature pick data from the dataset
 - Current view data model is loaded from query result 
 - Developing the search function in data and selecting cells 
 - Showing  resultant cell ids with different colors
 - Code review and gather feedback on the development efforts
 - Writing unit tests for js functions 

Aug 1 – Aug 7
 - Improving visualization and fixing svg bugs
 - Testing new developed features with sample data
 - Test Case improvements and bug fixes
 - Improve functional performance 
 - Review test cases and improve d3 transition 
 - Ensure compliance of my written code with Montreal C3G nodes code standards

Aug 7- Aug 14
 - Document the development steps
 - Sample use case preparation
 - Final Code review and improvements
 - User documentation update
 - Final Report preparation 

##### 	Aug 15: Final week

Aug 15 - Aug 23
 - Finalize User documentation
 - Discuss future improvements

##### 	August 23: Submitting final evaluations to Google

## Management of Coding Project

### Deliverables
The main deliverable for the project will be adding smooth negation with advance navigational features for DIG viewer and improve data analysis process over the multiple dimensions data set such as epigenomics experiment results in DIG Viewer. It would include above features. 

 - Case Study with newly added features for DIG viewer
 - Research on multiple dimensions visualization techniques
 - Depth researching on D3 js library for (Expanding and collapsing user interface elements, scrolling event, Data binding to the UIs (sync UI to data model), Data modeling and filtering, Partial selection mechanism in data grid, Data reading and writing with CSV, Data and UI querying)
 - Keep the C3G Montreal node documentation up-to-date with what I find/implement
 - Updating  my blog with posts 
 - Help create / edit / update markdown / bitbucket pages[3] with regard to my project
 - Keep the my project team / mentors updated on the current status
 - Follow good design, C3G Montreal node Coding Standards and Industrial best practices
 - Testing and documenting all the code
 - Collaborate and give my contribution to the community and teams in C3G Montreal node

### Implementation Plan
1.	Study the DIG Viewer codebase and use cases with epigenomics experiment results.
2.	Study D3 js library into depth regard to navigating multi dimensions data set. 
 - More into D3 core [7] which handling selections, transitions, data, localization, colors
 - D3 Scales which responsible for convert between data and visual encodings 
3.	Design a user friendly Rich GUI for data visualization, navigating and transitions
4.	Create mockup uis and use-cases for features
5.	Implement the features after confirming the features and the design with mentor and the community
6.	Design the new features
 - Expanding  and collapsing rows / columns in matrix with transitions
 - Visible matrix rows and columns titles when scrolling vertically or horizontally
 - When data model gets updated updating grid content
 - Filtering function for rows and columns
 - Partial cell content selection
 - Row-based grouping
 - Exporting current view of the grid to CSV files
 - Query the dataset rather than showing the full dataset in the view
 - Search data in matrix grid
 - Import CSV file to grid view
7.	Test features with use-case / sample data set
8.	Start implementing  features and do code reviews
9.	Write test cases for each feature that is implemented
10.	Provide detailed and completed Documentation related to the project
11.	Documenting newly added features for the APIs
12.	Share my experience on blog, emails with community
 
## Test
I have completed full selection test (4/4) with two approaches simple html version and also with nodejs version (industrial pattern). Developed application codes are available online on my github repo [d3-visualization-html](https://github.com/Madhuka/d3-visualization-html) [11] and [d3-visualization-demo](https://github.com/Madhuka/d3-visualization-demo) [12] respectively. Each repo have share screen shots of achievements and readme file. 

| Task                                                                                                                                                                | Status    |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| Step 1: Create an HTML document that uses D3 to display the following JSON document as a table with headers                                                         | Completed |
| Step 2: Make that table sortable when clicking on headers                                                                                                           | Completed |
| Step 3: Draw a pie chart displaying sepalWidth for versicolor species, falling in these categories: (<=2.5), (>2.5 and <=3), (>3 and <= 3.5), (>3.5 and <= 4), (>4) | Completed |
| Step 4: Make this pie chart display the same data as in step 3, displaying 1 species every 5 seconds. Use D3 transitions when switching to another species          | Completed |

## Future Implementations
1. Extend D3 visualization interface where can be zoom in and out.
 - Zoom in will give more details selected cells
2. Adding interactive to the DIG Viewer
 - Dragging, Coloring, Cropping the grid with smooth transitions

## References
[1] http://computationalgenomics.ca/home.html

[2] http://epigenomesportal.ca/ihec/

[3] https://bitbucket.org/genap/digviewer

[4] http://epigenomesportal.ca/ihec/grid.html

[5] https://bitbucket.org/mugqic/gsoc2016/overview#markdown-header-development-of-an-html-dynamic-matrix-to-represent-datasets-with-multiple-dimensions

[6] https://cwiki.apache.org/confluence/display/ZEPPELIN/COMDEV-119+Zeppelin+GSoC+Project%3A+add+more+D3+visualization

[7] https://github.com/mbostock/d3/wiki/API-Reference

[8] Pickett, Ronald M., and Georges G. Grinstein. "Iconographic displays for visualizing multidimensional data." Proceedings of the 1988 IEEE Conference on Systems, Man, and Cybernetics. Vol. 514. 1988.

[9] Dzemyda, Gintautas, Olga Kurasova, and Julius Žilinskas. "Multidimensional data visualization." Methods and applications series: Springer optimization and its applications 75 (2013): 122.

[10] Schroeder, Michael P., Abel Gonzalez-Perez, and Nuria Lopez-Bigas. "Visualizing multidimensional cancer genomics data." Genome Med 5.1 (2013): 

[11] https://github.com/Madhuka/d3-visualization-html

[12] https://github.com/Madhuka/d3-visualization-demo
