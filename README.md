# Archery Scoring idea:

## Contents
* [Overview](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#overview)
* [My reasoning to create this project](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#my-reasoning-to-create-this-project)
* [How I expected the project to go](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#how-i-expected-the-project-to-go)
* [What went well](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#what-went-well)
* [What didn't go well](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#what-didnt-go-well)
* [How the project could be improved](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#how-the-project-could-be-improved)
* [The project](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#the-project)
* [External documentation](https://github.com/DylanPatel11/Archery-Scoring/blob/main/README.md#external-documentation)

## Overview

## My reasoning to create this project



## How I expected the project to go


## What went well



## What didn't go well
When creating my entities I realsied to start the idea off I was thinking about every little detail and should have thought about the idea being simple. What I mean by this is for each session there are alot of variables such as the differernt settings on a bow, the different arrow setups and different session environments ect. Thus I decide to narrow down my variables. Another problem arose when naming my columns. For example I wanted to date each session that was recorded but DATE is a reserved word in MySQL so I changed the column name to "dated" for now. In the future I will make the names of each column neater.
When trying to connect to the H2 database I could see that I had my SpringBoot application connecting with MySQL creating the table however I was unable to connect to the H2database through my browser. I was struggling to find the problem when I realised the java file in the entity package I named 'session.java'. "Session" is a reserved word also therefore I had to change my entity java file to "shoot.java".
When pushing to git hub I strugged emensly

## How the project could be improved



## The project


## External documentation
All external documentation linked to this project can be found in the documentation folder in main branch. The link to my Jira board for this project is linked bellow.

[Jira Board](https://dylan-patel.atlassian.net/jira/software/projects/AP/boards/5 "Dylan's Archery Project Jira Board")
