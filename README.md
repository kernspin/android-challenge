# android-challenge

Coding challenge: Create a small Android app that takes location data from a server and displays the information.

# Scope
- Use common libraries (for DI, networking etc.) to structure your app. Use Jetpack Compose for the UI.
- Get location data from https://payback-coding-challenge.s3.eu-central-1.amazonaws.com/germany.json
- Determine the current geo location of the device.
- Have one screen that shows one editable textview (to enter search text) and a button to clear the input.
- Below that show a scrollable list of the loaded location data. List items show the name of an item, the address and the distance to the current location. The list is sorted by distance to the current location.
- While typing text into the search textview, the list should be be filtered on the fly and only show items containing the search string.
- Write a unit test for one component of the application.


# Some starting point for discussion
- What makes your solution an efficient implementation? 
- What and how would you test your code?
- How would you handle a change of the data source, e.g. a different data format? 

# Delivery
Fork this repository and make your solution publicly available. 
