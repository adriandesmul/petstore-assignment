HOW TO RUN
==========

1. Download dependencies using npm 
----------------------------------
Navigate to project root folder and type npm install`.
*Depending on your system, you might need to execute npm with admin rights.*

2. Download dependencies using bower
------------------------------------
Navigate to project root folder and type `bower install`.

3. Build dist
-------------
Navigate to project root and type grunt dist`

4. Start server
---------------
Navigate to project root folder and type 
`./node_modules/json-server/bin/index.js --watch src/server/db.json --routes src/server/routes.json --static src/client`

ASSIGNMENT
==========
Introduction
------------
The Scrum team went through one week of development (of a two weeks sprint), and delivered this petstore project to CVS. Your role as a QA automation engineer, is to create the UI testing based on the user stories by using [Robot](http://robotframework.org/) and [Selenium](http://www.seleniumhq.org/).
You will find below the users stories and DoD that might guide you on your journey.

The product owner is going to use your automated tests to validate the work the team has done.

User stories and DoD
--------------------
[Link to the user stories and DoD](../assignment/USER-STORIES.md)

SAMPLE
======

![alt text](../assignment/sample.png "App look")