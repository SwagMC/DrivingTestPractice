# final-project-bbq
final-project-bbq created by GitHub Classroom

# How to Run:
Clone this repo into local directory.

Install MongoDB.

Create 3 collctions of "users", "questions" and "results" in MongoDB.

Open three terminals and run these commands:

First terminal:

$ cd into local project directory
  
$ npm install

$ export PATH=<local mongodb directory>/bin:$PATH
  
$ mogod
 
Second terminal:

$ node server.js

Third terminal:

$ ng start

Now you can access the app at http://localhost:4200/login.

# Code Structure:

Components: /src/app/components

APIs: /api

Resources: /src/assets

# Driving Test Website
   ## Basic function:
    1. User registration
    2. User login
    3. User modify password
    4. User answer test
    5. Upload test questions
   ## Additional features:
    6. Analysis of tests results
    7. Driving school location recommendation
# User Story
   According to the above project design, there are two types of people to use this website: admin and users.
   
   ## Login 
   As a admin, she/he wants to login the website, so she/he can effectively view his work history and update website information.
   
   As a user, she/he wants to login the website, so she/he can review his own history record every time.
   
   ## Register
   As a user, she/he wants to register the website, so she/he can have her/his user account, and then she/he can login the website,to view her/his historical test records and analysis, which can help her/him more effectively do the test.
   
   ## Modify password
   As a user, she/he wants to modify the password, so she, he can avoid the risk of being stolen after a password is compromised.
   
   ## Test
   As a user, she/he wants to do the test, so she/he can better prepare better before the official exam.
   
   ## Upload test questions
   As a admin, she/he wants to manage the test function, so she/he can help the website to attract more users to the website.
   
   ## Analysis of tests results
   As a admin, she/he wants to know the analysis of tests results, so she/he can more specifically update a specific type of questions and the difficulty of distinguishing them.
   
   As a user, she/he wants to know the analysis of tests results, so she/he can conduct exam review more specifically.
   
   ## Driving school location recommendation
   As a admin, she/he wants to recommend the driving school location, so she/he can help the website generate revenue.
   
   As a user, she/he wants to get the information of driving school location, so she/he can know more quickly about his driving school information and then she/he can get a driver's license faster.
   

## Domain Model:
https://github.com/neu-mis-info6150-fall-2018/final-project-bbq/blob/master/BBQ%20Diagram.svg
