# Overview of UFO analysis


Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

# Result


Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.


# Summary
Overall, the theme and background image matchs the UFOs content very well. Multi-filters work functionally. Still, the webpage can be improved a little bit. 
  1. A drawback of this webpage
     
     The data source is limited. The observation record of UFOs only covers the date from 1/1/2020 through 1/13/2020. This is unsufficient for a webpage. More data need to be collected. If it is impossible to get more date, there should be a remarks beside `Enter Date` filter to clarify the date period.
  
  2. Two additional recommendations for further development 
     
     1. The text `Filter Search` is very frustrating for the users. It looks like a filter button, quite misleading. At the same time,  `UFO Sightings` button which is for unfiltering is on the very top corner. Users might not notice it. For the further improvement, I would suggest to create two buttons: `Filter Search` and `Go Back` right above or below the filters. `Filter Search` will triger the filter to show the filter results after user input the filters and click the `Filter Search` button. Whereas `Go Back` will take over the function of `UFO Sightings` button. It will help user to go back to unfiltered table.
     2. The filter input must be exact macth to the format of data value in database. Currently, the input of city, state, country must be lower case. Even though there are examples for each filter, they are not popular format for common use. If we can add a couple of code line to igonre or convert all input uppercase letter to lowercase letter, it will provide users a better experience on searching.
     
