# UFO Sightings

## Overview

The purpose of this project was to store UFO sighting data in a JavaScript array and create a table that organizes and displays the data. The table includes five filters that makes the table dynamic, meaning that it can take user input and display UFO sightings depending on the input that was entered. The data can be filtered on more than one criterion at the same time. The filters are UFO sighting date, city, state, country, and shape of the UFO. In addition to these fields being displayed in the data, the table also includes duration of UFO sighting and additional comments. The table is contained within an HTML file allowing it to be easily used and viewed as a webpage.

## Results

### Webpage Upon Opening

When the webpage is first opened, the table is not filtered at all. The filter boxes do include sample data that can be entered, but these are simply placeholders. You can determine whether the text in the box is a placeholder or not by the color of the text. Placeholder text is grey and entered criteria text is black.

![1_InitialScreen](https://user-images.githubusercontent.com/115508658/213566982-e9beeedb-8ec0-4a83-81fa-8c5c2182685a.png)

### How to Filter the Table

In order to filter the table on any of the five possible search box criteria, you can simply type the result you would like to find into the box, and then press enter. You can filter the table on more than one criteria at a time, as long as a record exists in the table for the multiple criterion. City, state, country, and shape entries must be all lowercase. If a record does not exist with the input criteria, only the table headers will be displayed. 

#### One Filter

![2_OneFilter](https://user-images.githubusercontent.com/115508658/213567745-fc8a7b5d-1eaa-4468-95a6-ffedddacdde1.png)

#### Two Filters

![2_TwoFilter](https://user-images.githubusercontent.com/115508658/213567753-9bed1d17-ab13-4aa9-bd39-cf27c4ddaf6e.png)

## Summary

One drawback to the design of this table is that there is no visibility to the possible criteria options that you may enter. If a record does not exist for an input, or if an input is misspelled or contains uppercase letters, the table will not return any results. One recommendation for further development is to modify the search boxes to include all possible options available to filter on in a dropdown menu. Another recommendation is to allow input to not be case sensitive.
