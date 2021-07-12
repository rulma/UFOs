# UFOs

## Overview of Project

The purpose of this project was to create a website able to display data in an informative table. Within the site the suer will be able to filter the table view based off of several criteria. The table with automatically update and allow for quick filtering and narrowing of user's desired results.

## Website Walkthrough

#### Landing Page
![Landing](https://github.com/rulma/UFOs/blob/d0c72d2d89dd3c8bffbb3e5b26b6a7a0ffd6a7a2/site%20pics/Landing%20Page.PNG)

Above we see the landing page that the user will first see when directing to our site. It includes our title, some fancy space art, and a quick paragraph summarizing the conent that will be found in our data table.

#### Viewing the Table

![Prefilter](https://github.com/rulma/UFOs/blob/ad684923f75d769dec071abacf341e4081ec4841/site%20pics/Prefilter.PNG)

The user can then scroll down the page to locate the table. On the left is the filter table box. Within this box the user can provide different criteria they would like to filter the data on.

#### Apply Filters

Next, we will go through the steps of filtering our table to show the user exactly what they want.

![First Filter](https://github.com/rulma/UFOs/blob/ad684923f75d769dec071abacf341e4081ec4841/site%20pics/first%20filter%20w%20dates.PNG)

Here we see that the user has applied their first filter, "1/1/2010", in the date section. Once the user has entered the date and clicked out of the input box the data will automatically filter. There is no button press needed. Our website dynamically changes based off of any inputs received in our input boxes. The following images will display the addition of more filters and how it narrows down our table.

**Second Filter**
![Second Filter](https://github.com/rulma/UFOs/blob/ad684923f75d769dec071abacf341e4081ec4841/site%20pics/second%20filter.PNG)

**Third filter**
![Third Fitler](https://github.com/rulma/UFOs/blob/ad684923f75d769dec071abacf341e4081ec4841/site%20pics/3rd%20filter.PNG)

**Final Filter**
![Final Filter](https://github.com/rulma/UFOs/blob/ad684923f75d769dec071abacf341e4081ec4841/site%20pics/final%20filter.PNG)

## Summary

As we can see our site allows users to customize the display of data and provides a nice readable format for them to view it. Unfortunately, our website could be improved as they are several issues with it as it stands. Currently, there is no error catching on our site. This means that a user could enter in the wrong datatype for one of our filters and there is no indication to let them know that it is incorrect. In addition, if a user enters in the letter "A" into one of our text inputs, the website will return every instance of data that contains the letter "A".

To improve our site, we could take the following action. First, we should implement some level of error handling and easily display this to the user. So, if they were enter in an invalid date or data type they would prompted to correct it. Also, we could create a way of the user to save filter settings. This would allow them to save table displays that they may use often.
