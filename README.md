# Lost Treasure:
## Statement of Purpose:
In this app we are going to create a game mainly for the students of Northwest Missouri State University.The main target devices for this game to work on are iPhone SE,laptop,ipad and an Android device.This game helps the bearcats to explore various places on campus and helps in building team work by working in teams.This game is similar to that of treasure hunt. We will take certain area into consideration and make them into blocks mainly 10x10. Players earn points whenever they reach the set location which is also called as "Destination".Each player can create a team and can play together.They can also enter into a competition and can compete with each other. 

## Game Vision:
We would like to create an app that can be played on a mobile device. The app would encourage players to complete a 'quest' by encountering a specific list of locations. A player would activate one of the locations in the quest. In order to score points, the user must enter the geographic area (as determined by their mobile device). Locations may be explicitly identified (easier) - or described using clues (harder). The quest may require locations to be accessed in a specific order - or in any order as specified by the quest creator.
 

# Team Members and Their Roles
1. Rajeshwari Rudravaram - Team Lead
1. Puneeth Annam - QA Analyst
1. Rohith Chittimalla - Senior Developer
1. Chandrakanth Polisetty - UI Developer
1. Nooka Raju Boddu - Backend Developer
1. Vishal Reddy Vennavaram - Frontend Developer

# Mentor/Client
- Dr. Denise Case
- Assistant Professor, Northwest Missouri State University
- 44-691 Graduate Directed Project

# Consultant
- Dr. Charles Hoot
- Northwest Missouri State University

# Jira Project Link Of Proposal Document
[Jira Project Link](https://gdp01.atlassian.net/secure/RapidBoard.jspa?rapidView=1&projectKey=GH&selectedIssue=GH-6)

# Sprint1 in Jira of Lost Treasure app
User stories

![Sprint 1](Sprint1.png)


# Given Tasks
[Request for Proposal Document](https://github.com/denisecase/rfp-hunt/blob/master/rfp-hunt.md)

# RFP-HUNT GAME

## Mission statement
The main purpose of this treasure hunt game is to develop physical and mental fitness in people.Day-by-day human-beings are becoming lazy due to this COVID-19 pandemic, so by developing these kind of apps one can bring activeness among individuals.

## Overview of this game

- We might want to make an application that can be played on a cell phone. The application would urge players to finish a 'mission' by experiencing a particular rundown of areas. 

- A player would enact one of the areas in the mission. To score that area, the client must enter the geographic territory (as controlled by their cell phone). Areas might be expressly distinguished (simpler) - or depicted utilizing hints (more diligently). The mission may expect areas to be gotten to in a particular request - or in any request as indicated by the journey maker.

## ER Diagram:

 ![ER Diagram](https://github.com/Rajeshwari-Rudra/GDP1/blob/master/FinalERDiagram.png)
 ER Diagram for this game consists of various entities like Team,User,Player,competition,Quest,Location.
 * Each user may be part of any number of teams and participate in many competitions.
 * A Team may or may not have Players and even Player can or can not be a part of team.
 * Competition can be independent of Team and Team can also be a independent of Competition.
 * Quest can contain zero or many locations,Location can contain optional quests.
 The ER Diagram shown above consists of the following attributes.They are User,Team,Quest,Location,Competetion,Player,TeamPlayer,Location of Quest,TeamCompetition.
 
 # User Entity:
  The user entity consists of Username as primary key.The other attributes of user consists of Email,password,Datecreated,DateLastaccesed.A user has to register while entering into the game.A registered user may be a part of a single team or may be a part of multiple teams.
 
# Team Entity:
   The entity team has the following attributes.They are TeamID as the primary key.The other attributes of this entity are TeamName,Creator,Datecreated,DatelastEdited and the username as the foreign key.

# Quest Entity:
   This entity consists of the following attributes QuestName,designer,datecreated and datelastaccesed. A quest can be created by the user and may provide with clues inorder to reach the location.
   
# Administrator Responsibilities
- A person who can authenticate and can authorize regarding this app.

# Role of a User 
- A person who can able to fetch all the information about the app.

# Drawbacks that can occur

- When internet or mobile data is unavailable then the location of the player cannot be traced.
- A Player can not play the game without registration and here the assumption is "Player is accepting all the terms and conditions".
- Score for each task is determined based on reaching the location or marked place within stipulated time.And for groups the score is determined based on the whole performance of individual members.



