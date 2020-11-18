# ALLIED AIRCRAFT MISSIONS OF THE VIETNAM WAR 1965-1975

*An historical data storytelling of US and Allied airborne missions during the Vietnam War.*

<br>

![Intro](https://github.com/NickCunnington/Vietnam/blob/main/final_map_images/overview.png)

<br>

## Where is the final presentation?

The presentation for this project is in ArcGIS Story Maps format and is available as a webpage at:

https://storymaps.arcgis.com/stories/ee9e2ca5e68e4c41887bb4832ee6f89f

<br>

## What is this project about?

This project is based around a dataset which is part of the Theatre History Of Operations (THOR) Datamil project.  It includes 4.5 million entries of aircraft missions during the Vietnam War by the US and some allied forces.  I wanted to suppliment some of the exploratory findings I have made in the data with an historical background, so this is also in part an historical research project.

<br>

## Where does the data come from?

This large dataset is produced by the US Defence Digital Service and has been released for public interest.  It is available from:

https://data.world/datamil/vietnam-war-thor-data

As this dataset is big (3.06 GB) I am not able to upload files to GitHub.  If you want to be able to run the R code then you will need to download the dataset your self from the link above and put the main `"thor_data_vietnam.csv"` file in the `rawdata` folder.

<br>

## How was the project produced?

The project has been completed in R, Python and ESRI's ArcGIS suite of software.  

* R was used for data manipulation and producing plots, 

![R](https://github.com/NickCunnington/Vietnam/blob/main/readme_images/R_wrangling.PNG)

<br>

* Python for data cleaning and manipulation using the ArcPy Jupyter Notebook module within ArcGIS Pro, 

![Python](https://github.com/NickCunnington/Vietnam/blob/main/readme_images/workbook.PNG)

<br>

* ArcGIS Pro for spatial workflows and production of maps, and 

![ArcGISPro](https://github.com/NickCunnington/Vietnam/blob/main/readme_images/subsetting_classes.PNG)

<br>

* ArcGIS Story Maps for the final presentation of the project in an HTML format.

![StoryMaps](https://github.com/NickCunnington/Vietnam/blob/main/readme_images/story_maps.PNG)

<br>

## What reference material was used?

Plots and maps were produced from the THOR Vietnam dataset by myself, pictures are credited to individual authors or websites using the `i` symbol on the image concerned and historical research from multiple sources as listed in the `credits` section at the end of the presentation.
