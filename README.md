# Overview of UFO analysis

This project is focusing on developing a dynamic webpage by inserting JavaScript data source into an HTML page. 
1. Build a table to hold and display UFO observation data.
2. Add a filter to take user inputs and refine the table accordingly through multi-filters. 
3. Insert the table into an well-structured HTML page.
4. Use bootstrap and css to style the webpage.
5. Add title and an article to webpage as a brief introduction for the analysis.

# Result

and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.
Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.


# Summary
Overall, the webpage looks nice. The content are coherent. Multi-filters work functionally. The theme and background image match the UFOs content very well. Still, the webpage can be improved a little bit. 
  1. A drawback of this webpage
     
     The data source is limited. The observation record of UFOs only covers the date from 1/1/2020 through 1/13/2020. This is unsufficient for this webpage. More data need to be collected. If it is impossible to get more date, there should be a remark beside `Enter Date` filter to clarify the date period.
  
  2. Two additional recommendations for further development 
     
     1. The text `Filter Search` is very frustrating for the users. It looks like a filter button, quite misleading. At the same time,  `UFO Sightings` button which is for unfiltering is on the very top left corner. Users might not notice it. For further improvement, I would suggest to create two buttons: `Filter Search` and `Go Back` below multi-filters. `Filter Search` button will triger the filter to show the filter results after user input the filters and click the `Filter Search` button. Whereas `Go Back` will take over the function of `UFO Sightings` button. It will guide user to go back to unfiltered table.
     2. The filter input must be exact macth to the format of data value in database. Currently, the input of city, state, country must be lowercase. Even though there are examples for each filter, these are not popular format for common use. If we can add a couple of codes to igonre or convert all input uppercase letter to lowercase letter, it will provide users a better experience on searching.
     
