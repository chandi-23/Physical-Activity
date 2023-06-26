#Flex Appeal

### Clone the repo
```bash
git@github.com:neu-mis-info6150-spring-2022/final-project-flex-appeal.git
```

## Description
Flex Appeal is a one-stop, all-inclusive solution for fitness tracking. This web application allows users to keep a record of their daily health indulgences ranging from food, water, exercise, sleep, active activities etc. And observe progress over time. 

This application will be developed with a responsive UI styled using SASS which uses ReactJS that is supported by a scalable NodeJS backend that uses the ExpressJS middleware to route its requests to appropriate business logic functions. User input as well as the information displayed on the application’s various pages are recorded using MongoDB. The app also uses several open-source APIs to support additional features such as weather, events, sharing, etc.

### User Stories
- As a user, I can login. 
- As a user, I can create my profile. User profile will have personal details such as name, age, gender, height, weight, date of birth, location (city and country), and photo. 
- As a user, I can update my profile at any time. 
- As a user, I have access to a dashboard landing page with infographics about calories burned, calories consumed, goal calories, sleep hours, etc. over a period (daily/weekly/monthly/yearly). 
- As a user, I can view my best personal records on a leaderboard. 
- As a user, I can view health status (sleep aggregate, calorie aggregate, etc.) on a weekly basis. 
- As a user, I can click on a stat and have options to view more details and/or update. 
- As a user, I can add and update a daily “fitness journal” about food and water consumed, exercises pursued. When updating food records, I can view calories contained in each food. 
- As a user, I can view the fitness journal of any given day when we click on a certain day in a calendar. 
- As a user, I can view activity events in a certain area.  
- As a user, I can check the weather prior to pursuing a certain activity with suggestions on indoor vs outdoor activity. 
- As a user, I should be able to “flex” my “appeal” (share stats on social media). 
- As a user, I can sign out. 

### Dependecy

- Node version - v12.6.0 and above or (LTS)
- NPM version - v6.0 and above or (LTS)
- SASS compiler - v1.49.9 or (LTS)
- mongoose - v6.2.9 or (LTS)

### How to run

- Install the above mentioned dependencies.
- Clone the repo.
- Running front-end web application - Change the directory to web-app and run the command. 
```bash 
npm start
```
- Running backend server -  Change the directory to web-app and run the command.
```bash 
node server
```

### Team Members
- Ruthwik Ravi Kumar Soudry - 002926233, soudry.r@northeastern.edu
- Sai Siddhartha Kondamu - 002961108, kondamu.s@northeastern.edu
- Stuti Singh - 002953126, singh.st@northeastern.edu
- Varun Venkatesh Gowda - 002126161, gowda.v@northeastern.edu
