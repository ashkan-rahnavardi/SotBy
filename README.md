# SotBy

## Context
  &ensp;The faculty of BCIT's Automotive Department were using a shared google file to manage vacations, resources and schedules, which led to a lot of confusion and inefficiency.

  &ensp;Only one person could edit the file at a time, and there was no way to track changes. Due to the lack of error control, if an error was made in the file it would be difficult to find and fix.

## Scope 
  &ensp;This project was going to eventually replace the old system, and would be used by the faculty to manage their schedules and resources.

  &ensp;I was apart of the second team to work on this project. The first team had developed a semi-functional backend which had most of the functionality required for the project. My team was given a 4 week sprint to develop a userfriendly frontend for the application.

## Objective
  &ensp;My teams objective was to develop a user friendly frontend for the application, as well as implementing a secure login system for various account types.

  &ensp;Admin account types would be able to edit the schedule, resources and vacations of all users. Faculty account types would be able to edit their own schedule, resources and vacations.

## Challenges
  &ensp;The main challenge we faced was learning how to use the backend that was developed by the previous team. We had to learn how to use the API endpoints that were developed, and how to use the database.

## Implementation
  &ensp;The team before us had developed a backend for the application using a PERN stack. We used this backend to develop the frontend for the application using React and Material UI.

 &ensp;We also implemented a secure login system using JSON Web Tokens and bcrypt. The login system was able to differentiate between admin and faculty account types, and would only allow admin account types to edit the schedule, resources and vacations of all users.

## UI / UX
  &ensp;We decided to make each column in the calendar represent a week, this would allow the user to see the schedule for the entire month at a glance. We also decided to make the calendar view the landing page, so that the user would be able to see the schedule for the current month without having to log in.

  &ensp;Once logged in users are able to interact with the calendar in order to edit their schedule, request resources and request time off.

## Next Steps
 &ensp;The next major step for this project would be to host the application on a server. This would allow the application to be used by all faculty members at BCIT.

 &ensp;Additional testing and optomization would also be required to ensure that the application is stable and secure.
