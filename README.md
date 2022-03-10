# UFO Javascript

## Overview of the Project
For this project we are building an HTML page that will allow us to pull up information from a javascript data file using filters on the page. Intent is to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## HTML Page and results

![image](https://user-images.githubusercontent.com/96096924/157742033-88731baf-6fc3-4e1d-bac3-72bb07c4d459.png)

Once entering the website our client will see the basic opening and title with the picture at the top, as the client scrolls down they will begin to see all the data and filters that we have(which is in the image below). From this image below we have 5 different filters to choose from; the date, city, state, country & shape. You can choose any of these filters enter the search bar, then the HTML page will show all of the sightings for that specific search. Multiple filters can be entered at the same time to further inspect the data in the specific search bar that is entered.

![image](https://user-images.githubusercontent.com/96096924/157742195-62a833fa-4521-414e-9a9a-f2572e78f6d1.png)

Below there are a few examples on how to filter data:

1) You can filter by one or all of the search criteria shown. For example, if you search by "City", you will see that the table updated to show the reported sightings that was recorded for that specific city. In the below example we enter bonita and leave other filters as is, see below outcome:

![image](https://user-images.githubusercontent.com/96096924/157747445-fdd961d0-20c0-41d0-a48d-997a2d2f2884.png)

2) The next example will use 2 filters in this case will delete the bonita filter and add a filter by date and state. So below are the results for "1/10/2010" in the state of Texas. You can see that the 2 filters applied are in black versus filters not used in grey.

![image](https://user-images.githubusercontent.com/96096924/157748050-b2e360df-0770-421c-b0ee-e2ac87afc194.png)

## Summary

### Drawbacks:

Unfortunately, the page has several drawbacks. They include:

-The search field is "case-sensitive". The table will not update if you do not enter exactly how the data is stored and does not allow for partial entries. This is an issue because it does not intuitively tell the user how the information should be entered other than the "default" example shown.

-There is no button to click, wording or action that tells the user that the table will update after you hit "enter".

### Recommendations:

With the following enhancements, it can greatly improve the user's experience.

-Add additional customizations, such as click-buttons, dropdown list, and/or auto-fill that can help "guide" the user and make the page more interactive.

-Add functionality to pull the data from a live source that includes current and archived data not limited to only the United States, but globally.


