# Syllabus
Welcome to GEOG 441, Advanced Geospatial Methods

## Course Objectives
This course is designed to allow students with varying degrees of GIS and remote sensing experience to increase their knowledge.  The class is mainly focussed on Python, R and other open source geospatial tools.  Students are free to choose the exercises that are most relevant to their goals.

That said there are a few skills and tools that students need to grasp by the end of the class.
+ Use of GIT for project management and code sharing
+ Basic Understanding of GDAL
+ Ability to use either Python or R to perform geospatial tasks


## Grading

| Component | Fraction of grade  |
|-----------|--------------------|
| Exercises           | 0.3 |
| Independent project | 0.3 |
| Group Project       | 0.3 |
| Participation (coming to class, being engaged)       | 0.1 |

### Exercises
There are two exercises that are required, one introducing GIT, and another introducing GDAL. Students may choose other exercises based on their interests or project needs. We will be using GIT to manage projects in this class, and GIT is a skill that many employers are interested in.  GIT is also a great way to manage and share your own projects if you are a researcher.

I am forcing you to learn a little about GDAL for a couple of reasons.  The first is historical/contextual. Most other geospatial applications rely, at least partially, on GDAL.  It has been in use since 2000.  Secondly, it is extremely useful. It is great for writing scripts for processing files in batch.  If you ever want to process a bunch of files in a container on the cloud it is a good choice because it does not have complicated dependencies.

The rest is up to you as far as exercises go.  You do however need to make substantial gains in you ability to use either R or Python (or both!) to solve geospatial problems.  Ideally, by the end of the quarter you will be familiar with the content of the suggested tutorials for your chosen language and have completed at least on of the synthesizing exercises.  If you are working primarily with your programming language for your personal project, or group project you can skip the synthesizing exercise if you would like.    

At the end of the quarter you will submit a brief __self-evaluation__, with a summary of the exercises you have completed and a paragraph or two describing the things you have learned.  You will give yourself a grade for the exercises portion on the class, and explain why you deserve that grade.

+ GIT exercise (required, complete by 2025-04-09)  
    + Create a github (or [similar](https://www.wearedevelopers.com/en/magazine/298/top-github-alternatives)) account (if you don't have one)
    + Read and experiment with the steps in this [Github tutorial](https://rogerdudler.github.io/git-guide/)
    + Clone this github repo
    + Create your own repo for your individual project
    + With your group, create a repo for your group project
    + Before you start working on group project, mess around with commits, branching and merging to get some practice.

+ GDAL tutorials (required)
    + In the Spatial Thoughts [GDAL tutorial](https://courses.spatialthoughts.com/gdal-tools.html#basic-raster-processing) do sections 1.1&ndash;1.4 and 2.1&ndash;2.3

+ Python tutorials
    + [Numpy](https://foundations.projectpythia.org/core/numpy.html)
    + Pandas:
        + [10 minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
        + [Intro to data structures](https://pandas.pydata.org/docs/user_guide/dsintro.html)
        + [Essential basic functionality](https://pandas.pydata.org/docs/user_guide/basics.html)
        + [IO tools (text, CSV, HDF5, …)](https://pandas.pydata.org/docs/user_guide/io.html)
        + [Indexing and selecting data](https://pandas.pydata.org/docs/user_guide/indexing.html)
        + [Ways to select from Pandas DataFrames](https://pandas.pydata.org/docs/getting_started/intro_tutorials/03_subset_data.html)
    + GeoPandas:
        + 
    + rioXarray:
        + [Xarray](https://foundations.projectpythia.org/core/xarray.html)
        +
    + Synthesizing exercises:
        + 
    
+ R tutorials

+ QGIS tutorials
+ GRASS tutorials
+ Other stuff you want to learn tutorials



## Calendar

| Week | Date | Lecture | Preparation |
|----|--------|---------| ------------|
|  1 | 2025-04-02 | Introduction <ul><li>Wait... It's possible to do GIS without ESRI?</li><li>Why learn Python or R?</li></ul> Introduction to Tools<ul><li> git</li><li>conda</li><li>VScode</li><li>Rstudio</li><li>QGIS</li><li>GDAL</li><li>GRASS | |
|  2 | 2025-04-07 | Group Project Introductions  <ul><li>9:00 - Devin Best: Land Trust Water Conservation</li><li>9:15 -Tiffany Faulstich: Arbretum Mapping Project</li><li>10:45 - Beaver Damn Analogue Site Suitability</li>11:00 - Reed Kenny: Cal Poly UFEI, Mapping post-wildfire tree mortality in LA</li></ul> Individual Project Introductions  <ul><li>BYOP...</li><li>or I can help you come up with one</li></ul>| |  |
|  2 | 2025-04-09 | Python and R: <ul><li>Introduction and Comparison</li><li>Jupyter Notebooks</li></ul> | Complete the GIT exercise before class |
|  3 | 2025-04-14 | Working with Vectors in Python |  |
|  3 | 2025-04-16 | Working with Vectors in R <ul><li>Rstudio</li><li>R-markdown</li><li></li></ul> | |
|  4 | 2025-04-21 | Working with Rasters in Python <ul><li>rasterio</li><li>rioXarray</li></ul> __Or Drone flyin'__| |
|  4 | 2025-04-23 | _Working with Rasters in R_<br>__Or Drone flyin'__| |
|  5 | 2025-04-28 | _Working with Rasters in GRASS_ <ul><li>_Watershed Delineation_</li><li>_Landforms_</li></ul>  __Or Drone flyin'__| |
|  5 | 2025-04-30 | _Lidar_ <ul><li>_PDAL_</li><li>_pdal-python_</li></ul> __Or Drone flyin'__| |
|  6 | 2025-05-05 |  Catch up day| |
|  6 | 2025-05-07 | Lidar continued <ul><li> Crown Delineation in lidR </li><li> Archealogical stuff with Open Lidar Toolbox in QGIS</li><li>lidR</li></ul> | |
|  7 | 2025-05-12 | Group Project Check-In | |
|  7 | 2025-05-14 | Individual Project Check-In | |
|  8 | 2025-05-19 | Leaflet, quarto, reveal | |
|  8 | 2025-05-21 | Subject By Popular Demand | |
|  9 | 2025-05-26 | Memorial Day | |
|  9 | 2025-05-27 | Subject By Popular Demand (A Tuesday following Monday schedule) | |
|  9 | 2025-05-28 | Subject By Popular Demand | |
| 10 | 2025-06-02 | Individual Presentations| |
| 10 | 2025-06-04 | Group Presentations| |


# Lectures
Lecture Slides found [here.](https://kulpojke.github.io/geog441/)

# Individual project ideas
Difficulty Ratings:  
Easy <progress value="1" max="100" style="accent-color: red;"></progress>  
Hard <progress value="100" max="100" style="accent-color: red;"></progress>

Project Ideas:
+ <progress value="25" max="100" style="accent-color: red;"></progress> [Get a part 107 Commercial UAV operators license](https://www.faa.gov/uas/commercial_operators/become_a_drone_pilot).  Study for the test, then take the exam (costs $175).
+ <progress value="30" max="100" style="accent-color: red;"></progress> Here are some ideas in the realm of [urban planning](https://medium.com/@animagun/5-open-source-gis-projects-for-urban-planning-you-can-build-this-weekend-2c820cb10f3c).  You would need to go above and beyond just following the steps presented in this article, but they could be a good starting point. This article is Python focused, but you could redo them using other tolls if desired. 
+ <progress value="50" max="100" style="accent-color: red;"></progress> [Do something cool with Carbon Mapper data](https://carbonmapper.org/data)
+ <progress value="75" max="100" style="accent-color: red;"></progress> Train an ML model to identify abandoned cannabis grow operations in the Klamath Mountains.
+ <progress value="85" max="100" style="accent-color: red;"></progress> Build an application or module/library for accessing the [ESA Climate Data API](https://climate.esa.int/en/data/apis/)


# Group Project  
Below are details of the group project.
 
 ## Final Project Outline - April 21st

Submit a one-page outline with the following sections: 
	+ Introduction - Describe the setting and problem. Why is it important?
	+ Background - What is the necessary context to understand the problem being addressed and what work has been done by others related to the problem.
	+ Study Goals - What is the goal of the analysis.  What will be delivered.
	+ Methods - What methods will be used to accomplish the goals.
	+ Data - What data will be used to accomplish the goals
	+ Expected Results - If applicable, what do you expect to find in the study? 

## Final Project Draft - May 12th

Submit a draft of your report with 
	+ Introduction
	+ Background
	+ Study Goals
	+ Methods and Data
	
If you have any results you can include those too

## Final Project Presentation and Webpage - June 4th

    + Give a 15-30 minute presentation on the project.
    + Have a complete project webpage (We will talk about how to do this using github pages soon.  Don't be intimidated, its not that hard.)
    + An efficient way to handle both tasks is to make your presentation slides on GitHub pages.
    
## Final Project Report - June 4th

Submit a report (As a PDF) describing the problem, your analysis, and your findings.  The data you produced should also be made available for use by stakeholders or ohter parties.

Use the following structure for the report: 

1. Introduction and Background
	+ Description and Importance of the problem
   	+ Previous work done on the problem
   	+ Goals of analysis, and (if applicable) what you expect to find
	+ Map of your study area

2. Data and Methods
	+ What data will you use to investigate this question? Include:
		- Table summarizing the data you used with brief description
        - Maps depicting data, if needed.
	+ Describe your analysis methods including:
        	- Text describing your procedure
        	-Processing diagrams / flowchart of data processing steps
        	- Figures and maps, as necessary

3. Results

	+ What did you find from the analysis? Include:
        	- Maps showing results
        	- Tables and figures (with captions) as necessary.
    	
4. Discussion

	+ Were the results what were expected?
	+ Did the analysis answer your question?
    	+ How do these results recontextualize the original question?
    	+ What assumptions were made in the analysis?
    	+ What are sources of error or shortcomings of the study?
    	+ What further analysis would you perform? 

5. Conclusions 

    	+ What would you have done differently?
    	+ What further work should be done? 

6. References
	
	+ You can choose the citation format, so long as it is consistent.
	+ Run it by me to make sure it is a reasonable format.
	+ Include an in-text citation for claims made like this (Author, year)
        	- For example: “In riparian habitats,  aardvarks show a preference for nesting in oak trees (Horkenborkenstiein et al., 2025).”
        	- OR: "Horkenborkenstiein et al. (2025) found that in riparian habitats,  aardvarks show a preference for nesting in oak trees."
    	+ Each cited source should be listed in the references section in alphabetical order.

7. Contributions - describe who did what. 