# UFOs
User-Driven Data Visualization on Dynamic Webpages

#### by Christopher Madden

## Overview of Project
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

The key concepts covered in this module are as follows:
  1. Explain the strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+.
  2. Describe JavaScript syntax and ideal use cases.
  3. Build and deploy JavaScript functions, including built-in functions.
  4. Convert JavaScript functions to arrow functions.
  5. Build and deploy forEach (JavaScript for loop).
  6. Create, populate, and dynamically filter a table using JavaScript and HTML

## Results:

Here is what the top of the page looks like:

![Top of Page](https://github.com/maddenc33/UFOs/blob/main/static/images/top.PNG)

When first visiting the page, you can see the five filters on the left:

![Bottom of Page](https://github.com/maddenc33/UFOs/blob/main/static/images/bottom.PNG)

Here is an example of the filters in use.  By simply typing the desired date into the date search box, you can filter for only that date, as seen below.  Please note that the exact same type of date formatting must be used.

![Pic 3](https://github.com/maddenc33/UFOs/blob/main/static/images/date.PNG)


## Summary: 

#### Findings
This is a very basic search function.  It works well if the user knows exactly what to input.  It's as if a user must have prior knowledge of the data set before using this function.

#### Drawbacks
Search inputs are case sensitive.  Some shape descriptions such as 'formation' and 'light' are not intuitive, so a user without prior knowledge of the data set is unlikely to enter these search terms.

#### Recommendations
Here are two recommendations I would suggest for improving the functionality of the search tool:

  1.  Make it so that the search inputs are not case sensitive.  When I searched for El Cajon, I found no results until I searched in all lower-case:

  ![El Cajon](https://github.com/maddenc33/UFOs/blob/main/static/images/el_cajon.PNG)


  2. Add the option to filter a date range rather than a single date.
