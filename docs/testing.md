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



## Test Runs

### Test Case ID testing:

| Use-Case ID| Requirement ID| Test Case| Status|
| ---------- | ------------- | -------- | ---------- |
| use-case 1| FR1.1| The system shall get the users geo-location from navigator.geolocation| Pass|
| use-case 1| FR1.2| The system shall get the nearest public toilets from the database| Pass|


### Use-Case / Functional and non-functional requirement testing:

| Use-Case ID| Requirement ID| Test Case| Status|
| ---------- | ------------- | -------- | ---------- |
| use-case 1| FR1.1| The system shall get the users geo-location from navigator.geolocation| Pass|
| use-case 1| FR1.2| The system shall get the nearest public toilets from the database| Pass|
| use-case 2| FR2.1| The system shall get the information for the specified toilet from the database| Pass|
| use-case 1| NFR1.2| There is a user freindly default browser when there is no geolocation avaliable| Pass|
| use-case 2| NFR2.1| The data on the toilets should be as up to date and accurate as possible | Pass|
| use-case 2| NFR2.2| There is a user interface with suitable sized text so most users can read it| Pass|
| use-case 3| NFR3.1| If no toilets are avaliable at a certain time an error message should be displayed| Fail - UC3 is not fully implemented yet|
| use-case 3| NFR3.2| The app should have good performance to respond to user interactions quickly| Pass|



