<img src="assets/images/dungeonDragons.jpg" class="figure" alt="Lego Dungeons and Dragons - Action Points by Marco Hazard is licensed with CC BY-SA 2.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/2.0/">


# DnD and Data Science Group Project

## Introduction

In the Mastery Project, we took a project from raw data through ETL to infographics with a final report.  Many times, projects require breaking the work across teams.

Today, help your instructors with an Excel dashboard that can help them run a Dungeon and Dragons game (5th edition). Your dashboard should include the ability to schedule some games.  The goal is to have fun.  We have for this project outsourced other teams to get the DnD data.

To better understand the data or to play, here is the Basic Rules for DnD
* https://dnd.wizards.com/articles/features/basicrules
* https://media.wizards.com/2014/downloads/dnd/DMBasicRulesv.0.3_PrinterFriendly.pdf

## Use this DnD Data Set.
The data will be provided in the general channel.
The original data set is from https://www.kaggle.com/shadowtime2000/dungeons-dragons



## Instructions

You have been assigned into teams of 3-4. One team will be the Back End Team, and one team will be the Front End Team.  You decide which team should complete what effort.

### Hour 1:

#### Back End Team

Use the part 1 CSVs to create an ER diagram.  In this ER data, also model the functionality so people can schedule a game and this should include a place ( possibly digital, in-person, hybrid), a time/day the game will take place, and people who will be attending.

Check-in with the Front End Team in 30 minutes and share your ER diagram.  Discuss and refine the ER diagram and dashboard based on the discussion between teams. 


#### Front End Team 

Sketch out a dashboard that will eventually connect to an Azure database through Excel. The dashboard will be used as an aid to a dungeon master, and a fast place to schedule a game. 

Check-in with the Back End Team in 30 minutes and share your dashboard.  Discuss and refine the ER diagram and dashboard based on the discussion between teams.  At this meeting, the teams should agree on the ER diagram and this diagram cannot be changed without each team coming to a consensus.

### Hour 2 onward:

#### Back End Team: 

* Create the SQL to create the tables.  Use script from the [Gen 10 teams](https://genesis10.sharepoint.com/sites/Dev10April26DataProfessional/Shared%20Documents/General/Supplemental%20Materials/Module%205%20-%20ETL/scripts/Class-ERD-Souvenirs.sql)
* We have a DBA ( Tom Seeber) to assist you if you need any help translating the ER Diagram to the DB and getting your Database going.
* Create a Data Factory to load set 2 of the CSV files into your database.

Hint: Prioritize loading Part 1 CSV's into your Database so the Front End Team has some data to work with.  

#### Front End Team: 

* Use the limited data set to start building a functional dashboard to help the DM and keep refining the dashboard with iterative improvements.  You may need to investigate and use VB in Excel to complete this task.

#### Additional Front End Resources:

##### Dash boards 

* https://www.thesmallman.com/dashboards
* https://www.youtube.com/watch?v=20zDV9MNE0s

##### Macro Programming in Excel: 

* https://www.excel-easy.com/vba/create-a-macro.html
* https://www.excel-easy.com/vba.html



### Final Presentation 
At the end of the Lab, each pair of teams will demo their Dashboard to the class.


## BONUS 1:
Replicate the Dice Rolling https://www.wizards.com/dnd/dice/dice.htm in the Dashboard for DM's to use.
Hint:  This may require VB and Macros in excel.


## BONUS 2:
Once the Dashboard is set, use the "Basic Rule set" and Dashboard to play a short game.
