# UFOs
## Overview

The purpose of this analysis was use javascript in order to filter a website that contains a list of information about ufo sightings.

----
## Results
### PART 1 "Creating the website" 

-The creation of the website was pretty straight forward as it came from the initial work of the module in which HTML and CSS code was used in order to provide a visually appealing layout:

![Screenshot](https://github.com/chgallegos/UFOs/blob/main/static/images/website_layout.png)

-The next step was to add the new elements needed for table filtering, this was done by adding the following pieces of code below the original input field for the "Filter Search" field:

![Screenshot](https://github.com/chgallegos/UFOs/blob/main/static/images/filters.png)

### PART 2 "Javascript app"

-In this part of the analysis, with the use of a starter code, pieces of code were added in order to take the input from the user and hold into a variable. This input needed to match the id of the type of input, which was verified by looking at the console in the devTools of the browser.

![Screenshot](https://github.com/chgallegos/UFOs/blob/main/static/images/filter_input.png)

![Screenshot](https://github.com/chgallegos/UFOs/blob/main/static/images/console_check.png)


-Lastly, the filter inputs needed to be looped and replaced by the use of a for loop.

![Screenshot](https://github.com/chgallegos/UFOs/blob/main/static/images/filter_loop.png)


### PART 3 "Using the website"

-The use of the website is pretty straightforward, the basis of it is to use filter parameters in order to locate ufo sightings based on the search criteria. This is simply done by inputing either, date, city, state, country or shape of the object. Keeping in mind that the placeholders of the search bars provide the an example with the correct syntax of the input needed for the filters to work. 

![Screenshot](https://github.com/chgallegos/UFOs/blob/main/static/images/filter_search.png)

-When the search criteria is inputted, the table filters itself automatically without needing to press enter nor a search button.

![Screenshot](https://github.com/chgallegos/UFOs/blob/main/static/images/search_example.png)

----
## Summary 

-In summary, the website does a great job in filtering the data. I would say that a drawback is that the values of the placeholders could be set to empty once a filter is inputted in order to avoid confusion when looking at the results. 

-I recommend having an export button that downloads the filtered data on a csv type of file in order to make it easier to analyze. 

-Another recommendation is to utilize a data scraping method in order to keep the website with the most updated UFO sightings as it is deployed and more sightings are included.