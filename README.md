# Health and Wellness App (HAWA)

## Purpose :

Have you ever wondered how healthy you are or how's your daily activity cycle ?

Every person is always busy or tend to forget to maintain their calorie or water intake and might also have an unhealthy sleep cycle which impacts their health. To maintain one's daily basic health activites , we are proposing an application , "Health and Wellness" which helps the user to track activities like amount of sleep,step count, consumtion of calories and hydration levels. Food habits of every user vary and they might not know how many calories they are consuming or burning. we'll help them to monitor their data by taking the user input.

## Overview :

Using this app, the user can monitor their activity and understand how they can improve or manage daily activities. Every user can set a personal goal for each activity and see if they can reach it or not. They can accept challenges created by admins and also can create their own challenge among their friends or groups.

As a Statista survey shows, 26 percent of 18- to 29-year-olds use apps to track nutrition regularly, while 23 percent in the same age category use them occasionally. Nutrition and diet apps help users track calories they consume and burn and control water balance. [Reference](https://www.statista.com/statistics/698919/us-adults-that-would-use-an-app-to-track-their-diet-by-age/)

With this app, users can set goals they want to reach, such as losing or gaining weight. To let users monitor their eating habits, apps of this type should have a food logging feature.

Motivating users is important for any type of fitness app. So we have friendly challenges which help users stay motivated too. This can be done by telling users how they can achieve goals, showing progress, sending push notifications etc.

This app calculates the number of calories to consume, taking into account a user’s goals and fitness profile. For food logging, the app has a barcode scanner that helps log foods and their nutrition values by simply scanning a barcode and automatically pulling information.

## Developer Roles :

| Group Members    | Roles                | Contact Information    |
| ---------------- | -------------------- | ---------------------- |
| Sindhuja Valeti  | Project Manager      | s538102@nwmissouri.edu |
| Tarun Sarpanjeri | Team Lead            | s537916@nwmissouri.edu |
| Annie Chandolu   | Full Stack Developer | s538306@nwmissouri.edu |
| Neelesh Saladi   | UI Developer         | s538300@nwmissouri.edu |
| Alekhya Jaddu    | Front-End Developer  | s538343@nwmissouri.edu |
| Vigneshwar Reddy | Database Engineer    | s538106@nwmissouri.edu |

## Mentor

##### This project is guided by:

- Dr. Charles Badami
- Northwest Missouri State University
- 44-691 Graduate Directed Project
- Fall 2020

## Client

##### We are developing this project for our client:

- Dr. Rhonda Beemer
- Northwest Missouri State University

## Link to Published Site :

[Website](https://annie0sc.github.io/gdp_group4/)

## Link to Repository :

[Repo](https://github.com/annie0sc/gdp_group4)

## Jira Board :

User Stories / Tasks created in Jira:

![jira_board](https://github.com/annie0sc/gdp_group4/blob/master/Jira_Sprint1.PNG?raw=true)

[jira board](https://sindhuvaleti.atlassian.net/jira/software/projects/GDP1/boards/2)

## User Stories / Epics / Tasks

### Sprint 1: LOGIN PAGE

Story: As a user, I want to create an account in the application by signing up.
Story: As a user, I want to login the application to monitor my activities.
Story: As a user, I want to reset the password for my account.

### Sprint 2: PROFILE PAGE

Story: As a user, I want to update my personal details such as height, weight, age, gender.
Story: As a user, I want to view my followers list who can view my activities.
Story: As a user, I want to monitor the summary of my daily activities.

### Sprint 3: EPIC - HOME PAGE

This epic story consists of subtasks of the home page in user’s perspective.

Story: As a user, I want to view all the activities at one place so that, I get a clear picture of my daily activities.
Story: As a user, I want to enter data manually, so that I can update the home page with new data of my today’s activities.
Story: As a user, I want to see if I have a healthy sleep pattern or not.
Story: As a user, I want to challenge my friends to beat my step count.
Story: As a user, I want to form group with different users so that we can have challenges among groups.
Story: As a user, I want to create a challenge and motivate my friends.
Story: As a user, I want to add friends so that I can compete with them.
Story: As a user, I want to concentrate on my daily calorie in-take.
Story: As a user, I want to stay hydrated by consuming the ideal amount of water.

### SUBTASK:

#### Step count

Story: As a user, I want to set personal goal and motivate myself to reach it on a daily basis.
Story: As a user, I want to update my step count to reach my personal goal.
Story: As a user, I want to view my past step count so that I can balance the activity.

#### Calorie in-take

Story: As a user, I want to monitor my daily calorie in-take.
Story: As a user, I want to set personal goal and update my calorie in-take each time to reach it.
Story: As a user, I want to keep track of my past calorie in-take to maintain balanced diet.
Story: As a user, I want to update the amount of fruits and vegetable servings.

### Sprint 4: CHALLENGES

Story: As a user, I want to view the challenges which I joined.
Story: As a user, I want to accept or deny the pending challenges.

## Entity Relationship Diagram :

![ERD](https://github.com/annie0sc/gdp_group4/blob/master/ERD.PNG?raw=true)

This the ERD of the proposed app.

## Sample data :

### User data

![user_data](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/1.PNG?raw=true)

This is the sample data for user input which stores user name as user_id, email address, full name, age, weight, height and passwords.

### Admin Information

![admin_info](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/Capture2.PNG?raw=true)

This is the database for admins which stores their unique admin_id, full name, designation and password.

### Challenges

![challenges](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/Capture3.PNG?raw=true)

The details of the challenges are stored here. It records the name, activity type, date created, date completed, number of people joining and the winner of the challenge. Additionally, the ID of the person who has created the challenge will be stored with the admin ID who is managing that particular challenge.

### Home

![home](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/Capture4.PNG?raw=true)

This is place that displays all the activities offered by the app; step count, sleep levels, hydration levels and calorie intake.

### Steps

![step](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/Capture5.PNG?raw=true)

This is where the total step count is stored with it's calculated distance and daily step count goal.

### Sleep

![sleep](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/Capture6.PNG?raw=true)

The sleep levels are gathered in this place. It keeps track of the user's daily hours of sleep required and actual number of hours slept.

### Hydration Level

![hydration_level](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/Capture7.PNG?raw=true)

User's daily hydration levels and the hydration goal is stored in this table.

### Calories

![calories](https://github.com/annie0sc/gdp_group4/blob/master/Sample%20data/Capture8.PNG?raw=true)

The total calories consumed by the user in a day and his/her calorie goal is stored here.

[Sample data in excel.](https://github.com/annie0sc/gdp_group4/blob/master/SampleData.xlsx)

## Cost Management :

![Cost_Estimate](https://github.com/annie0sc/gdp_group4/blob/master/Costestimate.PNG?raw=true)

[Cost estimate for the project in excel.](https://github.com/annie0sc/gdp_group4/blob/master/CostEstimate.xlsx)

## Schedule :

![Schedule_Management](https://github.com/annie0sc/gdp_group4/blob/master/Schedule.PNG?raw=true)

[Schedule Management in excel.](https://github.com/annie0sc/gdp_group4/blob/master/Schedule%20Management.xlsx)

## Acceptance Criteria :

1. The user has to login to the app using username and/or email and is password protected which will be encrypted to provide another layer of security.

1. If the user does not have an account, they have to register by giving their full name, email address and create a new password.

1. The admins have specific User-ID and password which are generated by the company and is unique to each individual.

1. The admins have access to change and modify data wwithin the app but will have to get explicit permission from the user if they want to make any changes to user data.

1. The admins also have the rights to create new challenges which can be open to public and/or can be suggested to a particular group of friends or individuals.

## Interface Sketches :

### Login

![Login Page](https://github.com/annie0sc/gdp_group4/blob/master/Proposed%20Screens/1%20LOGIN.PNG?raw=true)

This is the first screen that appears when a user or an admin logins.

### Sign Up

![Sign Up Page](https://github.com/annie0sc/gdp_group4/blob/master/Proposed%20Screens/2%20register.PNG?raw=true)

The user will be redirected to this page when (s)he has not registered yet.

### Profile

![Profile Page](https://github.com/annie0sc/gdp_group4/blob/master/Proposed%20Screens/3%20profile.PNG?raw=true)

The user can review and make changes to their profile as desired.

### Home

![Home Page](https://github.com/annie0sc/gdp_group4/blob/master/Proposed%20Screens/4%20Home.PNG?raw=true)

This page allows the user to track their daily step count, hydration level, sleep amount and calorie intake.

### Step Count

![Step Count Page](https://github.com/annie0sc/gdp_group4/blob/master/Proposed%20Screens/5%20Step%20activity.PNG?raw=true)

The user will be redirected to this page when (s)he has selected the step count option in the home page.

### Calorie Intake

![Calorie Intake](https://github.com/annie0sc/gdp_group4/blob/master/Proposed%20Screens/6%20Calorie.PNG?raw=true)

This page tracks the daily calorie intake levels of the user.

### Challenges

![Challenges Pages](https://github.com/annie0sc/gdp_group4/blob/master/Proposed%20Screens/7%20Challenges.PNG?raw=true)

The admin has rights to create new challenges which can be open to public and/or particular to a group of users.

Each user can create new challenges which has the options to take it individually or include friends or keep it open to public.

## Link to original RFP:

[RFP](https://github.com/cbadami/rfp-health-and-wellness)
