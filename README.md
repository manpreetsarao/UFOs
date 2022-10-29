# UFOs
Using JavaScript/Html/css/bootstrap
## Overview of Project 
In this project we analyzed the UFOs data. Initially, we a have UFOs data in the form of Array of objects. The data has different column ids like date, city, state country, shape, duration, and comments.  The main motive of our project is to sort that data for specific search criteria. To accomplish this, we mainly used fitter and arrow function. The first step of our project is to create a table then sort the data for a specific date. After that, we added more filters like search for a city, state, country and shape. 
## Results
For results, we need to use filters. So, results vary from search to search. If someone enters, “ca” in state box and another one enters “ar”, results will be different. So, every time when user changes his search criteria the results will be different. 

![Screenshot 2022-10-28 222044](https://user-images.githubusercontent.com/111101038/198841394-50185d71-303b-4928-9024-1f6709a11175.png)

![Screenshot 2022-10-28 222143](https://user-images.githubusercontent.com/111101038/198841400-02278f6d-b442-4d03-8200-51f781531d9d.png)


From the image we can observe that if we type San Diego in city box it shows me three results whose city column is matching with San Diego. As we changed our search from city to date like, 1/10/2010 of ca state so we have new data with other cities. If nothing matched with our search no data will return. 
## Summary 
 ### Drawback 
The only drawback that I can see is the search when nothing is matching with the search results. In this case user will see an empty table with column names if someone is not familiar with data then he might assume that this website is not working.
### Recommendations
My first recommendation is to show a pop -up when nothing is matching such as, “no matches” or anything else. 
The second recommendation is if someone is entering wrong search, like someone trying to exceed the date, there should another pop-like please enter a valid date or showing the date limit, like enter a date between this and this, so on. 
