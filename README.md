# UFOs
### Analysis
#### Overview of the analysis:
 Working with a web application with a single filter for UFO sightings based on Date.
 * Purpose of this project is to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the  same time. In addition to the date, I added table filters for city, state, country, and shape. This allows for not just a single search filter but a multiple search filter for UFO sightings based on provide data file. Used HTML, JavaScript, CSS, BOOTSTRAP to complete this task. 


#### Results:
Result is a working web application that allows search criteria for multiple search critera.  
Here is an example of the newly added search criteria for our web page in our html file.
Date, City, State, Country and Shape all are provided for user to use in a search. 
* A description on how to perform a search is as follows,  
* Once you pull your webpage up you will see 5 different options to input text. The default as the page is loaded is all data from data file is displayed on table. 

![Screenshot (31)](https://user-images.githubusercontent.com/94208810/151680217-6d820691-fe01-4d22-b8f7-1ad772e05f7d.png)

* When you enter your search criteria it will populate new data in the table. 
Once a user enters the search criteria the table to the left of webpage  would  populate the results that return a match. If you want just one specific search criteria then just enter data for that element. If you search for one criteria such as shape would show all sightings for that UFO shape. If you enter more specific data search like city and shape then it will list items that meet both city and shape criteria that user input into search box. If you put a city that is not listed in the data then it will populate a blank table because there is not data for that city.  This is a drawback to our webpage in my opinion. 
I created two functions inside our apps.js file to help with the task. One was creating a function called filterTable() and another function called updateFilters(). The updateFilters() function saves the element, vlaue and the id of the filter that was changed. The filterTable() function loops through all the filters and keeps any data that matches the filter vales. 

* The following is an example of user searching for city: "el cajon"  and shape as "light". 
 
![Screenshot (28)](https://user-images.githubusercontent.com/94208810/151679501-c8e37300-478c-4fbe-afb4-b1652952a4fe.png)







### Summary: 
* There are some drawbacks with this webpage is that it is limited to the data in the data.js file and you have to manually clear out the search text boxes to reset the search criteria or refresh the webpage. 

* Two additional recommendations for further development or drawbacks I see are limited data to search and filtering method. 
1. I would recommend adding a way to clear the search data. Add a Clear search button maybe and it resets the search boxes to default so each time a user inputs something in the specific text box it would automatically repopulate the search information not just the first time the user presses enter the search has been done on that input. As of now, you have to go and clear out search input boxes. 
2. I would add a way to search a broader scope of data. Right now we are limited to what is in the data file and may be hard to know what to search because every bit of information on UFO sightings in not listed in the data file. if you don't know what is in the data file you could not know what to search for even with user input boxes. It would come up empty because the data is so limited. 




