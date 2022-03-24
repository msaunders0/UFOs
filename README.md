# UFOs

## Overview of Project
The purpose of this analysis is to track UFO sightings using a filtered search function that allows multiple criteria as inputs by the user. The filters that can be utilized are date, city, state, country, and shape.

## Results
In order to begin using this web application, [click here](https://msaunders0.github.io/UFOs/), which will display the index.html file in the root directory. The UI contains a jumbotron with background image, introductory text, multiple search filter bars, and a table where the data is displayed. Each data object is displayed in a row, with multiple columns containing values including the date, city, state, country, shape, duration, and comments of each reported sighting.

The "Filter Search" section allows the user to apply filters to the data displayed in the table. The user can apply as many filters as needed, all of which will be applied simultaenously in order to precisely narrow down the results of the targetted search. Placeholder examples have been provided for each filter to assist the user. Because of our event listener code, the user can simply press the enter key after typing the desired input into one of the search fields in order to apply the filter to the results.

![image](https://github.com/msaunders0/UFOs/blob/main/Resources/filters.png)

The data table initially includes all data contained in the data.js file. Filters are used to target specific data of interest. The column headers used are date, city, state, country, shape, duration, and comments. 

Below is an image showing the results when a city filter is applied using the value "el cajon".
![image](https://github.com/msaunders0/UFOs/blob/main/Resources/results.png)

This next image shows the results after a 2nd filter is applied for the shape of the UFO, where the example value used was "triangle". 
![image](https://github.com/msaunders0/UFOs/blob/main/Resources/results_by_shape.png)

## Summary
Unfortunately, the drawback of this web application is that the data used has not been updated in quite some time. This limits the usefulness of this site. However, we could improve the application by building a form that allows a user to submit a new sighting to the database, which would be stored as a new object in the data.js file. Another potential improvement would be offering the ability to filter based on a range of dates, since currently the user can either view results from all dates or just one specific date. 

Although this application could be improved upon, it is functionally sound and serves as a proper demonstration of some of the useful features of the JavaScript language.
