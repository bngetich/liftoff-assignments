# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
An app that will help farmers manage their greenhouses. The application will collect sensor data(temperature, humidity, soil moisture ) and send it to ThingSpeak cloud for storage and analysis. It will notify the farmer of any environmental factors that will destroy their crops. A Rasberry Pi or Arduino can be used to collect the sensor data but for the moment I will be sending http requests with mock sensor data to ThingSpeak instead. I will then create a web client that will receive the data and visualize it and also notify the farmer when necessary. 
### Features
User Login: User will be able login and view a dashboard of their greenhouse
Visualization: User will be able to view live charts of sensor data showing environmental condition of their greenhouse
Notification: User can receive a notification of any environmental factor that can affect their crop
### Technologies
Spring Boot
Angular
MongoDb
### What I'll Have to Learn
Reactive programming using spring's project reactor and also how to send and receive data through REST APIs - use a public api for agriculture. It has been a while since I used Angular so I want to re update my knowledge.
### Project Tracker
https://github.com/bngetich/liftoff-assignments/projects/2
