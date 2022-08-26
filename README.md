# UFOs

[Link to Webpage](https://bishopce16.github.io/UFOs/)

## Overview of Project<br>
The purpose of this project was to build a dynamic webpage and to take data from a JavaScript array to create an organized a table to filter UFO sighting data on multiple criteria. The table was built with JavaScript functions to loop through the data and create a customized dashboard. Html, CSS, and Bootstrap was used to modify the aesthetics of the webpage.  


---

## Resource:<br>

Data Sources: data.js<br>

Tool used: Visual Studio Code, HTML, JavaScript, Bootstrap, CSS<br>


---

## Results:<br>

Welcome/First encounter of the webpage:<br>
The Truth Is Out There webpage presents visitors with a dark background and light font with an image displayed using the style.css file.<br>

![the truth is out there webpage](static/images/truth_is_out_there_webpage.png)<br>

---

Filter Search:<br>
Below is the default table that is displayed when the webpage opens.

![ filter search table default](static/images/filter_search_table_default.png)<br>

The UFO sightings data was filtered on multiple criteria, including city, state, country, and shape.<br> This was accomplished by using JavaScript functions to loop through the data. The filters include event listeners that record information when an element is changed to develop an interactive webpage based on user’s input.

![ filter search table date 1/2/2010](static/images/filter_search_table_date1:2:2010.png)<br>
The search criteria displaying results for date "1/2/2010" above and city "benton" below.

![ filter search table city benton](static/images/filter_search_table_city_benton.png)<br>

  
---

## Summary:<br>

An if statement was added to the app.js file on line 70 to display “No results found” for a search that does not exist, instead of a default filled table.<br>

![“No results found” display](static/images/filter_search_table_noresultsfound.png)<br>


![if statement code](static/images/if_statement_code.png)


---

Addresses one drawback of this webpage:<br>
* The search field is case sensitive and requires lower case and correct spelling. 
* The data is also limited as it is not liked to a live source. 

---

Recommendations for further development:<br>
* Adding a scraping functionality to pull data from a live source that includes archived and current data. 
* Add further customizations for example a dropdown list, auto fill, or click button to make the webpage more user friendly and to remove the case sensitivity. 

---
