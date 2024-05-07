# Testing

## Test Plan

### Test Case ID: 1

Test: Is the user sent a notification to grant location permissions when the web-app is opened?
Test Steps:
-User opens PottyPal.
-Notification is recieved requesting location.
-








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





Test Runs
TODO: For each test described above, indicate the current status. 
Create a requirements traceability matrix to validate the completeness of the product.

| Use-Case ID | Requirement ID | Test Case | Status |
| ----------- | -------------- | --------- | ------ |

TODO: Add rows for each test, current status is eg. pass/fail




