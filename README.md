# UFO Sighting Analysis with JavaScript

## Purpose of Project

The purpose of the project was to create a website that would contain past UFO sighting data and putting that within a dynamic table that can be filtered on several key metrix within the data.
  1) Date
  2) City
  3) State
  4) Country
  5) UFO Shape

The user of the website can enter one of the filters or any number of the filters to narrow down their search for what they want to review.

![full page](https://user-images.githubusercontent.com/100856534/172065354-537dad25-c536-4431-8cea-40cca2ace9cb.png)


## Results After Creating the Webpage

After refactoring and adding in some code from the original website that was only able to be filtered by date, several other items were added for ease of the user and greater flexibility of the data

![filter section](https://user-images.githubusercontent.com/100856534/172065416-2f52a8c7-2816-45b8-94ba-941fb1d0cef4.png)


As stated before, and individual could either enter a single field or all filters can be populated. Either way the data would be populated. If no filters are added that all of the UFO sightings would be shown. Within each filter a suggestion is shown, for example "State" shows wi for Wisconsin, and the "Shape" shows a list of shapes available.  

**Using all filters at once**

![all filters](https://user-images.githubusercontent.com/100856534/172065988-4461229a-35e3-4117-95ce-95fbb7fd20cf.png)

Using all of the filters at once can get the data available down to a specific set of data. As shown above, Maricopa, Arizona only had one sighting on 1/1/2010. 

**Using only one filter**

![one filter](https://user-images.githubusercontent.com/100856534/172066000-8542e997-713d-4d7d-a313-fcd5f74922a5.png)

Only using one filter can give you a bigger snapshot of the data. For example, if you were interested in UFO sighting that did not have a defined shape, this can be pulled up by looking at the "Shape" filer and entering "unknown."


There is a great number of filtering options that can be done on this data, and as the data grows that filtering functionality will be even more powerful. 

## Summary

The amount of data that this simple website can manage will be beneficial for those that want to research UFO sightings all over the world. However, I can see some improvements that may need to be added in future website iterations. 

### Drawbacks
  1) No option for users to export the data they filter. Unless the user has web scraping knowledge that data would be hard to get to.
  2) If you do not type the filter exactly as it is in the data set then the filter will not provide any data. For example, if you were to type in Arizona as AR instead of ar, the filter will not provide you with any information, even though Arizona does have several entries. 

### Suggestions for Improvement
  1) For the filtering inputs these should be made into drop down selections as well. This way the user can either type what they want or pick from what is populated within the data. This would aid in eliminating the AR vs ar issues for States, and would also allow for other filters, such as, "Shape" to be more useful.
  2) Allow for the user to export the data.
