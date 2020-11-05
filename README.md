# Progressive Budget Tracker

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, the user can populate the total when brought back online.

![issues](https://img.shields.io/github/issues/kbnewlon/workout-tracker)
![GitHub top language](https://img.shields.io/github/languages/top/kbnewlon/workout-tracker)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
## Description 
 Fitness Tracker 2020 uses a Mongo database with a Mongoose schema, routes are handled with Express along with front end connections to the aforementioned routes. Use this application to view, create and track daily workouts. The user can log multiple exercises in a workout on a given day. Fitness Tracker 2020 allows the user to be able to track the name, type, weight, sets, reps, and duration of exercise. If the exercise is a cardio exercise, the user can track the distance traveled. 
<br><br>
 "Blessed be our New Founding Fathers and America, a nation reborn. May God be with you all" -The Purge

## Table of Contents 
* [Installation](#Installation)
* [Usage](#Usage)
* [License](#License)
* [Contributing](#Contributing)
* [Tests](#Tests)
* [Visuals](#Visuals)
* [Links](#Links)
* [Questions](#Questions)

## Installation
1. Use 'git clone git@github.com:kbnewlon/workout-tracker.git' to clone the repo
2. Install necessary dependencies with 'npm install'
3. Make sure that you are running 'mongod' in the background to connect to database 
3. Start the program with 'npm start' or 'node server.js'

## Usage
1. Enter new workout at "enter new workout here" field
2. Click 'enter new workout' button to enter new workout 
3. Add different exercises to the workout including sets, reps, weights, and notes pertaining to the workout
4. Delete workout with 'delete workout' button
5. Prepare for the end of this world with this workout app
6. Enjoy! 

## License
Copyright (c) 2020, Kayla Newlon. (MIT License)

## Contributing 
No guidelines at this time. 

## Tests
Feel free to contact me for any test ideas. 

## Visuals
![screenshot of homepage](public/assets/images/screenshot_homepage.PNG);
![screenshot of workout](public/assets/images/screenshot_workout.PNG);
![screenshot of entered workout](public/assets/images/screenshot_entered_workout.PNG);

## Links
To Repo: https://github.com/kbnewlon/workout-tracker
<br>Visit the deployed app on Heroku to demo: https://preparingfortheapocalypse2020.herokuapp.com/
 

## Questions 
Please contact me if you have any questions at:
<br>Email: kayla.b.newlon@gmail.com
<br>Github: https://github.com/kbnewlon














# Unit 18 PWA Homework: Online/Offline Budget Trackers

Add functionality to our existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

- - -

## Commit Early and Often

* One of the most important skills to master as a web developer is version control. Building the habit of committing via Git is important for two reasons:

1. Your commit history is a signal to employers that you are actively working on projects and learning new skills

2. Your commit history allows you to revert your code base in the event that you need to return to a previous state

* Follow these guidelines for committing:

  * Make single purpose commits for related changes to ensure a clean, manageable history. If you are fixing two issues, make two commits

  * Write descriptive, meaningful commit messages so that you and anyone else looking at your repository can easily understand its history

  * Don't commit half done work, for the sake of your collaborators (and your future self!)

  * Test your application before you commit to ensure functionality at every step in the development process

* We would like you to have well over 200 commits by graduation, so commit early and often!

* Deploy your application with [Heroku and MongoDB Atlas.](../04-Important/MongoAtlas-Deploy.md)

## Submission on BCS

* You are required to submit the following:

  * the URL to the deployed application

  * the URL to the Github repository

