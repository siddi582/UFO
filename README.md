# UFOs
*A JavaScript Interactive web-page*

## Overview of Project
### Purpose

The purpose of this project is to build a **dynamic web-page** that displays UFOs sightings information for upcoming annual gathering of UFO enthusiasts in McMinnville, Oregon. There is a lot of data to display so adding filters to the table which let users to refine their search on more than one level is absolutely necessary.  
The web-page contains the following:

-	Interactive filters for searching criteria on date, city, country and shape.
-	Brief article and its summary.
-	An attention-grabbing header with a refresh-page button.
-	Visually appealing design of overall presentation of the data.

<p align="center">
<img src="graphics/Header.PNG" width="80%" height="80%">
</p>
<p align="center">
A snippet from the header of the webpage.
</p>

### Background
For this project I am using **JavaScript** as the primary coding language. JavaScript is a scripting or programming language that allows to implement complex features on web pages (1). It is a lightweight OOP (object-oriented programing language) also known as a front-end development language and is most commonly used as a part of web pages. JavaScript adds extra functionality and customization to web-pages in order to enhance user experience (2). Besides JavaScript I am also using the following to build the dynamic web-page:

-	The data for the table is stored in a JavaScript array. [data.js](static/js/data.js).
-	The table is built by inserting **JavaScript** into HTML page. [app.py]( static/js/app.js).
-	**HTML** to build the webpage [index.html](index.html).
-	**CSS** and **Bootstrap** to build and style the page [style.css](static/css/style.css)
-	**Chrome Developer Tools** to test the code.


## Resources

- **Data Source:** JavaScript list [data.js](static/js/data.js)
- **Software:** VS Code and Chrome Developer Tools, 
- **Languages:** JavaScript, HTML, CSS and Bootstrap 3
- **Dependencies:** D3

## Results
Raw data from JavaScript array is now displayed in a dynamic table where users can filter data on multiple criteria by **date**, **city**, **state**, **country** and **shape** of UFOs sighting. In the filter input box is suggested text of how search criteria should be entered by user. For example, date should be entered in format as in 1/10/2010 – with forward slashes and without extra 0 before day and month. City, state and country should be entered in lower case.

<p align="center">
<img src="graphics/TableFilter.PNG" width="20%" height="20%">
</p>
<p align="center">
Dynamic multi-filter.
</p>

When user types desired criteria in multi-filter and then press enter the table displays only rows that matches the user input. From the picture below we can see only data that has been filtered based on the user input – that is -- *State: ca, Shape: light and Date: 1/1/2010*.
<p align="center">
<img src="graphics/FilteredTable.PNG" width="40%" height="40%">
</p>
<p align="center">
New table, displays only the results that matches the users input.
</p>

When resetting the filter, the user has two choices. User can either can clear input manually deleting input cell by cell or click the refresh button *UFO Sightings* that can be found at the top left corner of the page. After the filter is cleared, the user can use filter again.
<p align="center">
<img src="graphics/ActiveText.PNG" width="30%" height="30%">
</p>
<p align="center">
Reset filter and refresh page button at the top left corner of the web-page.
</p>

## Summary
To build dynamic webpages that accept user inputs and visually adjust to reflect that interaction require quite a bit of work and patience. As I am pleased with the work, there is always room for improvement. At that opportunity, I would like to address some drawbacks and recommendations for further analysis.

### Drawbacks
•	**All the data is displayed at once** which makes the entire web-page quite lengthy.

•	**Reset button is too far away from the filter** which is inconvenient, especially on the smaller screens, when user has to scroll up to reach the reset button and clear out the filter. 

### Recommendations for further analysis

•	**Converting all input to lower case.** Adding additional line of code that that would convert all letters to lower case from user input. In this case, the search criteria capabilities have much wider range and will improve user’s experience.  For example, it wouldn’t matter if user types “CA” or “Ca” instead of “ca”, the code will still be able to process and find the results.

•	**Adding drop down-menu from the filter**. Sometimes users don’t know what exactly they are looking for and just exploring our web-page and its data. We could increase positive user experience by adding drop-down menu. In this case user won’t have to guess what options they have.

## Resources
(1)	What is JavaScript, Developer Mozilla: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript Web 27 Sep 2020.

(2)	Module 11. UFO Sightings with JavaScript https://courses.bootcampspot.com/courses/200/pages/11-dot-0-1-creating-dynamic-content?module_item_id=78211, Trilogy Education Services, 2000, Web 27 Sep 2020.
