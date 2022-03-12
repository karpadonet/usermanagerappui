# Usermanagerapp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.5.

# Brief application description

The web application supports the foolwing:
1. Logging in a user
2. Presenting a user dashboard
3. presenting the details of a specific user in teh dashboard.
4. Logging out a user

Notes:
1. The application does not support registering new users. Users were added to the database manually by sending new user data to the server via POSTMAN.

# Log In
The login page checks for whether the userName and password match the userName and password in the database, if not presents and error. If they match the user is redirected to the user dashboatrd.

![alt text](https://github.com/karpadonet/usermanagerappui/blob/main/log_in.png)

# User dashboard

The userdashboard presents all the users which are currently logged in. The presented list is automatically refreshed every 5 seconds, such that if any user logs out the list will be updated accordingly.

Per each user in the list it is possible to redirect to a user details page pwe each users, which provides some additional info. for that user.

![alt text](https://github.com/karpadonet/usermanagerappui/blob/main/dash.png)

# User details

The user details page, presents some additional information for a user which was selected in the user dashboard page.


![alt text](https://github.com/karpadonet/usermanagerappui/blob/main/user_details.PNG)




