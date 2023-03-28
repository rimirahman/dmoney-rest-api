# Dmoney-REST-API with newman

## Technology used:
- Postman
- Newman

## Project scenario:

1. Login to orange hrm demo site
https://opensource-demo.orangehrmlive.com/

2. Create 2 new employees and save it to a JSON list
3. Now go to PIM dashboard and search by 1st user name. Assert that the user is found.
4. Now click on the user from the search table and update id by random userid
5. Now again search the user by new user id from the PIM dashboard menu and assert that the user is found
6. Now logout from admin and login with the 2nd user from your JSON list
7. Now click on My Info menu
8. Select Gender and Blood Type and save it
9. Click on contact details and input address and email
10. Logout the user

## How to run this project
- clone the project
- give this command ``` npm i ``` and ``` npm run report ```


## Documentation:
- https://documenter.getpostman.com/view/25360486/2s8ZDeSdyy
- [Bug report.xlsx](https://github.com/rimirahman/dmoney-rest-api/files/10512390/Bug.report.xlsx)
- [Test cases.xlsx](https://github.com/rimirahman/dmoney-rest-api/files/10512391/Test.cases.xlsx)


![181](https://user-images.githubusercontent.com/122162468/214920462-20da7291-e123-468a-8c9a-d6131d7b2b46.JPG)
![Total test](https://user-images.githubusercontent.com/122162468/214920797-4a7f6a0f-7d7d-40e4-a933-8f5c9da8ed84.JPG)
