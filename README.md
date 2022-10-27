# CMPG-323-Project-4---30517249-
automating and testing web application using uipath


#what the project is about
The project is designed to help stakeholders automate tasks that are to easy and quick to do, this helps users to get enough time performaing important tasks and leave the automation to the robots. The project also allows users to test if the automation was successfull or not and if not this gives the user the opportunity to do error handling so as to fix the issues encountered during the debugging of the process.

#The functionality of the project
The project has four workflows namely Login, readCreateCategories, readCreateZones and readCreateDevices. Each have a open browser activity that will capture the information on the webapplication using the url of the application. On the webapp you get different functionalities depending on the interface of the page you currently on.
##Login page
On this page we have click event that allows you to click the login button and access the page where you have to input your credentials to login like email and password then another click event to click login.

##readCreateCategories page
The page has an ctiviy called read range that allows you to read values from an axcell file to created on the webapp. The from each row activity allows you to traverse each row in the axcell file to be used on the webapp and the body of the activity contains additional aactivities that helps populate the webapp like click event, typeinto event and select item to populate dropdown values. For testing values created I used theactivity called find element that searches for a particular created value and the get attribute activity that will map the value to find element then write line activity to write the value to the output panel. Lastly i have the activity called write range that works with read range to update value from the test result from false to true if the seach was successfull. The same process is also rapeated for readCreateZones and readCreateDevices pages.
