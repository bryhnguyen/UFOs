# UFOs

# Overview

This repository contains a web page built with HTML and JavaScript to display a collection of UFO Sighting reports in a table with filters that can be searched with user input.
Data is retrieved from the data.js file and is called by the app.js file using event handlers to add functionality to user inputs like form submission for filtering. The index.html file uses the Bootstrap 3 framework to display and organize elements like columns, text, and the table.  
The table contains headers Date,	City,	State,	Country,	Shape,	Duration, and Comments that uses a form submission to filter the results with functions from the app.js file by all terms except duration and comments. 

# Results

A search can be performed with user input in the fields "Enter Date, Enter a City, Enter a State, Enter a Country, Enter a Shape". There are sample terms that are displayed to serve as an example for what can be searched and the format. To the right side of the search fields, the table displays the results. 

![City_Sample](https://i2.paste.pics/d766ec837267a8d176a2d132e3042248.png)

Multiple filters can be used!

![Multiple_Sample](https://user-images.githubusercontent.com/95376544/156941765-3dd42abd-d033-4b61-839c-69b73010eaee.png)

![Multiple_Sample2](https://user-images.githubusercontent.com/95376544/156941881-eadc6938-24d7-4feb-977a-885b4a9236fb.png)


# Summary 

This web application successfully organizes and displays UFO sighting reports in a filterable table. As long as the user understands what they would like to filter by or if the desired values are included in the table, they can filter the results. This is a double-edged sword since a user might not possess that knowledge at the time of use. A city they may have heard in passing or conversation may not translate well when searched for. For example, my family's city, Sachse, would be difficult to search for as it is pronounced sak - see. 

The table can be improved by allowing the searchable fields to be sorted in ascending/descending order to allow users to view the bottom of the table in addition to the top. This may be possible in Boostrap 4 and later releases. An additional improvement to the organization of the table could be to add a sidebar menu to show all the available values for cities, states, countries, and shapes similar in a manner how available shoe sizes and colors can be selected on a eCommerce website. 
