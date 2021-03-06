# Django Coding Challenge

**Please make sure to go through the below details before cloning the repository**

**Goal**: REST API development, as per the below details

**Development of following items**
- **Registration API** with User Name, Email and Passowrd
- **Login API with Email** and Passowrd
- **Users Listing API** to get List of Names & Email
- **Profile Update API** to update the profile details like Name, Designation, Profile Picture and Team

**Scope of work**
- Create REST APIs for the below user journey
    - User should be able to register with Name, Email, Password.
    - Once the User is registered, the User should be able to Login with the same email and password.
    - Once the user is Logged in, the user should be able to list all the users present on the platform.
    - User list should contain the name and email address of the users.
- Get user listing API should be authenticated against the logged in users and should throw an error if it's not authenticated.
- Profile Update API where user can update Name,  Designation, Profile Picture and Team, This also will be an authenticated API
    - Proifle Picture - User will upload the profile picture this can be either through s3 bucket or local machine
    - Team - will be multi select from the predifined list provided below 
        - Development
        - Product
        - Design
        - Human Resource
- Database you can use MySQL / PostgreSQL.
- No need to host the APIs, You can directly submit the pull request against this repository and your code will be reviewed.


> :warning: [Designs Link](https://www.figma.com/file/2hbi9TlIZdxBB6jycyNWws?node-id=0:1#122675486) - This URL is only for the visualization of the flow and Only API development is required.


**Steps to follow to submit your code**
1. Fork the repository
2. Make your changes 
3. Submit the **Pull Request** from the forked repository 


**Please note: git push on this repository is not allowed and only pull requests (PRs) from the forked repositories are allowed**
 
Once you have completed the development, Please raise the pull request from your forked repository, and your work will be reviewed against:
- **Developed APIs & Models**
- **Coding Standards**
- **Readability & Reusability of code**
- **Code Quality and Size**

_This repository is meant to facilitate the interview process @Designstring and only referred candidates for the interview process are requested to access_

Happy Coding!!!
