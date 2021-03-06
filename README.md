# TransMapper: Transform the way of Mapping census data<br/>
<img src="img/Hackathon-logo.jpg" width="20%">
<img src="img/Hackathon_2_panorama.jpeg">
## Description<br/>
TransMapper is a light weighted web mapping application focusing on visualizing numeric data using the cartogram map, a map on which statistical information is shown in diagrammatic form. The project was the project submitted to 2013 Ohio State Big Data Hackathon sponsored by Google, Hortonworks, Teradata and USG,. The project is conceived, planned, executed and developed in 24 hours.

## Examples<br/>
### Census Data<br/>
![](img/data.PNG)

### Map View and NLP Search by Word Similarity<br/>
![](img/Screenshot%202019-02-22%2010.34.54.png)

### Text Cloud of Words in Census Variable Names<br/>
![](img/tagcloud.PNG)

### Wordle of Words in Census Variable Names<br/>
![](img/wordle.PNG)

### Hackathon Result (3/30 in ranking)<br/>
![](img/Screenshot%202019-02-22%2010.32.51.png)


## Wiki<br/>
<a href="help.html" target="_blank">Help</a><br/>
<a href="meta.html" target="_blank">Data</a>

## Installation<br/>
The installation is simple. Download the entire repository onto your desk and double click on on the index.html to launch the web application. (Tested on all major browsers: Firefox, IE, Safari, and Chrome)

## Usage<br/>
1. Once the respository is downloaded, double click the index.html in root of the repository.
2. Choose a variable (one of the hundreds of census variables) from the dropdown list to create a cartogram map.
3. You will see the distortion and resizing of each region on the map approportional to scale of the value of the variable.
4. Hover over each region to see the exact value.
5. You may also click on the >>> button to bring up the text/voice search. Give a key word and it will match all variables by either text or sound. This is an example of leveraging NLP to make data visualization more interactive.


## Techniques:<br/>
Implementation was based on using 6 Javascript libraries: d3.v2.min.js (for core visualization), cartogram.js (for geographic data cartogram transformation), natural.js (for NLP), topojson.js (for geotransforming geographic objects), jquery-1.10.2.min.js (for utility functions) and colorbrewer.js (for blind safe colors for mapping).


## Credits<br/> 
The core cartogram algorithm using d3.js was based on the previous work by [Shawn Allen](https://github.com/shawnbot/d3-cartogram/). Project finished by three developers (David (myself, team captain), Lucky, and Jakob).
