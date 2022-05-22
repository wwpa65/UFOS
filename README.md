# UFOS


## Overview of Project

We have developed a webpage with information on UFO sightings. The goal of this project was to develop a web page that has a dynamic table that provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria (date, city, state, country, and shape) at the same time. For this work, JavaScript (includiung functions, for loops, DOM, filter, d3 library), HTML, CSS (Bootstrap), 


**Software used:** 
- JavaScript
- JavaScript d3 4.11.0
- [CSS](https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css)
- HTML
- VS Code 1.67.2
- Git

## Results

The web page shows a heading (and a background image), a text describing about UFO sightings, and a form for the user to enter input (with placeholders) on the left, and the dynamic table on the right. 

User can filter the data table using one or more input fields. 

Here are some examples on how to filter the data table. 

1. To filter the table to show UFOs sighted on 1/13/2010
a. Enter date 1/13/2010 into the "Enter a date" field as follows (and hit enter). See the red rectangle below.
   Other fields have default placeholder and the input field is empty.

![Date Search](/images/date-search.png)

b. You will see the table as shown below.
![Date Search](/images/date-search-table.png)


2. To filter the table to show UFOs sighted on 1/13/2010 and in the state of California
a. Enter date 01/13/2010 into the "Enter a date" field AND "Enter a state" fields as follows (and hit enter). See the red rectangles below.

![Date Search](/images/date-state-search.png)

b. You will see the table as shown below.

![Date Search](/images/date-state-search-table.png)

3. Yoiu can go on by adding other fields as needed. Note: If you enter a field(s) where there waere no UFO sightings, then you will get anm empty table.

A part of the full webpage and the table is shown below.

![Date Search](/images/full-webpage.png)



![Date Search](/images/form-table.png)

## Summary

In summary, a webpage was developed by using JavaScript to display information on UFOS in a dynamic table where the user has the ability to filter data based on the five filter items (date, city, state, country, and shape of UFO). 

- Drawbacks

In this webpage, we have a form to enter input text (with a placehoder giving an example for the input field).  
One of the drawbacks using the placeholder in the webpage is described below. 
  - Placeholder dissapears when the user enters contents to an input element. If the user forgets the hint in the placeholder, it is difficult for the user   
    to enter the input.
  - User input(s) has to be cleared (deleted) manually or the web page needs to be reloaded for displaying the full table again.
  - It can take more space in the web form, especially for the readers (broewsers) in mobile devices. 

- Recommendations

To overcome the drawback described above, the following options are recommended.
  - Include clear, visible labels (with hinta and instructions) with a clear folr field 
    - Example: "Enter a date (in DD/MM/YYYY format)" as the label with empty field for the input.
  - Use a floating label inside the placeholder 
  - Disign the web form section by including a dropdown menu with list of items available for selecting into the input field. 
    - This will enable the user to interactively use the web form for entering input and filtering data. The code needs toi be modified for accepting the input item and to link it with the filters. 
  
  [Reference: https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder](https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder)
  
