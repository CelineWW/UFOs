# Overview of UFO analysis

This project is focusing on developing a dynamic webpage by inserting JavaScript data source into an HTML page. 
1. Build a table to hold and display UFO observation data.
2. Add a filter to take user inputs and adjust the table accordingly through multi-filter. 
3. Insert the table into a well-structured HTML page.
4. Use bootstrap and css to style the webpage.
5. Add title and an article to webpage as a brief introduction for the analysis background.

# Result

This dynamic webpage can be explored by doing following steps:
  - Open the webpage by clicking index.html
![tableData](https://user-images.githubusercontent.com/105877888/183300021-9cdf0929-f64d-4853-baea-75c98c0c3c41.PNG)


  - Browse the title, summary article, and table columns.
  - In the input fields at the bottom left, insert one or more filters, press `Enter` to refine the table. Multi-filter includes: date, city, state, country, and shape. 
![filters](https://user-images.githubusercontent.com/105877888/183300068-45127114-001a-4593-a319-142b1803a01e.PNG)

*An example multi-filter and its result:*
```
Enter Date : 1/1/2010
Enter a City: ----
Enter a State: ----
Enter a Country: us
Enter a Shape: sphere
```
![multiple filter](https://user-images.githubusercontent.com/105877888/183300081-f6e97679-f01f-4357-9b56-687da8b42df8.PNG)



  - Change the input to refilter the table or clear the filter input and then press `Enter` to go back to full table. User may also access to the full table by clicking `UFO Sightings` at the top left corner.

![tableData](https://user-images.githubusercontent.com/105877888/183300091-de1c20f3-8011-4b7e-8889-075b2477d817.PNG)



# Summary
Overall, the webpage looks nice. The contents are coherent. Multi-filter works functionally. The theme and background image match the UFOs content very well. Still, the webpage can be improved a little bit. 
  1. A drawback of this webpage
     
     The data source is limited. The observation record of UFOs only covers the date from 1/1/2020 through 1/13/2020. This is unsufficient for this webpage. More data need to be collected. If it is impossible to get more date, there should be a remark beside `Enter Date` filter to clarify the date period.
  
  2. Two additional recommendations for further development 
     
     1. The text `Filter Search` is very frustrating for the users. It looks like a filter button, quite misleading. At the same time,  `UFO Sightings` button which is for unfiltering is on the very top left corner. Users might not notice it. For further improvement, I would suggest to create two buttons: `Filter Search` and `Go Back` below multi-filters. `Filter Search` button will triger the filter to show the filter results after user input the filters and click the `Filter Search` button. Whereas `Go Back` will take over the function of `UFO Sightings` button. It will guide user to go back to unfiltered table.
     2. The filter input must be exact macth to the format of data value in database. Currently, the input of city, state, country must be lowercase. Even though there are examples for each filter, these are not popular format for common use. If we can add a couple of codes to igonre or convert all input uppercase letter to lowercase letter, it will provide users a better experience on searching.
     
