# Testing

## Test Plan

### Test Case ID: 1

Test: Is the user sent a notification to grant location permissions when PottyPal is opened?

### Test steps:

1.User opens PottyPal.

2.Notification is recieved requesting location.

3.The user presses accept and the permission is granted.



### Test Case ID: 2

Test: Is the map displayed with the correct markers for the public toilets?

### Test steps:

1.User opens pottyPal and grants location permissions.

2.User selects the option to open the map.

3.The map is properly displayed with the public toilets having marker icons displayed.



### Test Case ID: 3

Test: Is the dataset correctly displayed and alocated to each toilet correctly?

### Test steps:

1.User opens pottyPal.

2.User selects the option to find by type or searches a specific toilet.

3.The toilet is displayed with the correct information besides it.



### Test Case ID: 4

Test: Does it allow the user to find the closest toilet too them?

### Test steps:

1.User opens pottyPal.

2.User allows location permissions.

3.The user selects find nearest public toilet and it is displayed with the correct information.



Functional requirements
*Each number after the FR is appropriate for the coresponding UC number.


FR1.1 The system shall get the users geo-location from navigator.geolocation.

FR1.2 The system shall get the nearest public toilets from the database.

FR2.1 the system shall get the information for the specified toilet from the database.

FR2.2 when appropriate, the system will filter out certain toilets even if they are closer but do not have the correct facilities.

FR3.1 The system should provide directions to the required public toilet that is open.

FR3.2 The system should filter out any closed public toilets as well as aditional filters.



Non-Functional Requirements
*Each number after the FR is appropriate for the coresponding UC number.

NFR1.1 The public toilets outside of the users selected range should not be displayed (Usability).

NFR1.2 The app should have a user freindly default browser when there is no geolocation avaliable (Reliability).

NFR1.3 The app should work on a smartphone (Portability).

NFR2.1 The data on the toilets should be as up to date and accurate as possible (Functional suitability).

NFR2.2 The app should provide a user interface with suitable sized text so most users can read it (Usability).

NFR3.1 If no toilets are avaliable at a certain time an error message should be displayed to allow the user know there is no toilets avaliable.

NFR3.2 The app should have good performance to respond to user interactions quickly.





## Test Runs

| Use-Case ID| Requirement ID| Test Case| Pass / Fail|
| :---: | :---: | :---: | :---: | :---: | :---: |
| use-case 1| requirement 1| Test case 1| Pass|
| use-case 1| requirement 2| Test case 2| Pass|
| use-case 2| requirement 3| Test case 3| Pass|
| use-case 1| requirement 4| Test case 4| Pass|






