# Bugs-Sample
Below are some Bugs that I have identified during my work on previous projects.

**Description:**
https://www.demoblaze.com/
Login credentials not recognized for existing users. Users who attempt to log in with their existing credentials are unable to access their accounts. 
 
 **Steps to Reproduce:**
1. Go to the website's login page
2. Enter the username and password of an existing user
3. Click on the "Login" button to submit the credentials
4. Observe the response or error message

**Actual Result:**
The system does not recognize the provided login credentials. Instead of logging in successfully, an error message is displayed indicating that the credentials are invalid or unrecognized.

**Expected Result:**
The system should validate the entered username and password against the stored user credentials. If the provided credentials match an existing user, the system should grant access to the user's account, allowing them to log in successfully. No error message should be displayed in this case.

......................................................................................................................................................................

 **Description:**
https://www.demoblaze.com/
The forgot password feature is currently not set up in the web. Users who forget their password are unable to reset it through the application.

**Steps to Reproduce:**
1. Attempt to reset password for any user account
2. Observe that there is no forgot password link or button available
3. Attempt to reset password through any other means available
4. Note that it is not possible to reset the password without the forgot password feature

**Actual Result:**
The website's login page does not provide any option or functionality for password recovery. There is no "Forgot password?" link or button available for users to initiate the password reset process. As a result, users cannot recover their passwords if they forget them.

**Expected Result:**
The website's login page should include a clearly visible and accessible "Forgot password?" link or button. Clicking on this link or button should take users to a password recovery page where they can enter their registered email address or username. After submitting the necessary information, users should receive an email with instructions on how to reset their password. This functionality allows users to recover their passwords if they forget them.

......................................................................................................................................................................

 **Description:**
 https://www.demoblaze.com/
 "Remember" button missing from login window
 
 **Steps to Reproduce:**
1. Go to the website's login page
2. Examine the login window or form
3. Look for an option or checkbox related to "Remember me" or "Stay logged in"
4. Observe the presence or absence of the "Remember" button
 
 **Actual Result:**
 The login window or form does not include any option or checkbox for users to indicate whether they want the system to remember their login session. There is no "Remember" button available
 
 **Expected Result:**
The login window or form should include a checkbox or option labeled "Remember me" or "Stay logged in". Users should be able to select this option if they want the system to remember their login session. Typically, this option is represented by a checkbox that users can toggle on or off. The presence of the "Remember" button ensures that users have control over their session persistence.

......................................................................................................................................................................

 **Description:**
 https://www.demoblaze.com/
 Bank Manager Login doesn't have a window to put their credentials. When clicking on the "Bank Manager Login" icon, users are immediately directed to the application without being prompted to enter their login credentials. This presents a security risk as anyone can access the Bank Manager's application without proper authorization. There is no window to input the username or password which would otherwise restrict access to only authorized users.
 
  **Steps to Reproduce:**
  1. Click on the "Bank Manager Login" icon
  2. Observe that the application launches immediately without prompting for login credentials
  3. Note that anyone can access the Bank Manager's application without proper authorization
  
   **Actual Result:**
   Clicking on the "Bank Manager Login" icon launches the application without prompting for login credentials, allowing anyone to access the Bank Manager's application without proper authorization. Error Messages/ Codes: None displayed.
   
   **Expected Result:**
   Clicking on the "Bank Manager Login" icon should prompt the user to enter their login credentials before launching the application. This would restrict access to only authorized users, preventing unauthorized access to sensitive data.
