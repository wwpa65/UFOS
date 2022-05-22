# UFOS


## Overview of Project: Explain the purpose of this analysis.

We have developed a webpage with information on UFO sightings. The goal of this project was to develop a web page that has a dynamic table that provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria (date, city, state, country, and shape) at the same time. For this work, JavaScript (includiung functions, for loops, DOM, filter, d3 library), HTML, CSS (Bootstrap), 


**Software used:** 
- JavaScript
- JavaScript d3 4.11.0,
- [CSS](https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css)
- HTML

## Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.



## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

In summary, a webpage was developed by using JavaScript to display information on UFOS in a dynamic table where the user has the ability to filter data based on the five filter items (date, city, state, country, and shape of UFO). 

- Drawbacks

In this webpage, we have a form to enter input text (with a placehoder giving an example for the input field).  
  - Placeholder dissapears when the user enters contents to an input element. If the user forgets the hint in the placeholder, it is difficult for the user to enter the input.
  - It can take for space in the web form, especially for the readers (broewsers) in mobile devices. 

- Recommendations
  - Include clear, visible labels (with hinta and instructions) with a clear folr field 
    - Example: "Enter a date (in DD/MM/YYYY format)" as the label with empty field for the input.
  - Use a floating label inside the placeholder 
  - Disign the web form section by including a dropdown menu with list of items available for selecting into the input field. 
    - This will enable the user to interactively use the web form for entering input and filtering data. The code needs toi be modified for accepting the input item and to link it with the filters. 
  
  [Reference: https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder](https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder)
  
