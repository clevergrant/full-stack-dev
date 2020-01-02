---
title: Home 
navOrder: intro
toc: 1
---

# Introduction

In this class we will learn how to do full stack development.

As technology continues to evolve at an ever quickening pace it is becoming increasingly more difficult to be a full stack developer.

Through this class we will develop a full stack application, but how much we cover and what will be determined based on what you want to learn and how much we can tackle together.

Each class will consist of time spent in instruction followed by time spent for lab work. Lab work is an opportunity to work through assignments in class and to talk through assignments submitted in class.

# You are Qualified

We each have different backgrounds, different educations, and different levels of experiences in all aspects of life.

Your range of experiences uniquely qualify you to see solutions that others may not.

You are not an impostor here. You belong.

# Tentative Schedule

- Domain Driven Design - Discovering the parts of your application
- API Design and Documentation using the OpenAPI specification
- JavaScript fundamentals
- NodeJS Introduction, packages
- Express server and routes
- Implementing a mock API with OpenAPI Enforcer middleware
- HTML and DOM manipulation with JavaScript
- CSS and SASS with build tools


# About this Class

## What will this class cover?

This class will cover how to:

- Create a dynamic web app within the client (browser)
- Create a custom server on NodeJS
- Manage user sessions
- Communicate with databases and understand at the basic level how to organize them
- Write tests for your code
- Package your code into micro services

## About the Instructor

- **Name:** James Speirs

- **Education:**

    - Bachelors of Science at BYU in Information Technology with an emphasis in User Interface Design.
    
    - Masters of Science at BYU in Information Technology with an emphasis in User Experience.

- **Work:**

    - Currently working for BYU's Office of Information Technology as an architect and engineering manager.

- **Office Hours**

    - I don't have an office or set hours, but if you need some one on one time we can set up a time to meet.
    
    - I plan to have free time at the end of every class to answer questions too.
    
# Homework

Homework assignments will be posted to [Learning Suite](learningsuite.byu.edu).

# Final Project

- You will also build throughout the semester a final project of your choosing.

- You may choose to build your Final Project while we work in class on our in class application.

- Worth about 25% of your final grade.

## Requirements

- Build a full stack (client and server) web application using [JavaScript](javascript.md) and [NodeJS](nodejs.md).

    - Client application must be built on [Vue](vue.md). Using [Nuxt](nuxt.md) is acceptable because it is built on Vue.
    
    - Server application must be built on [NodeJS](nodejs.md).

- The entire application must be [containerized with Docker](containers.md).

    - Must be easily moved from one environment (computer) to another.
    
    - Container must be self initializing for first start up.
    
    - The objective here is that I should be able to download your project from Git and have it running in less than one minute.
    
- Must access it's own containerized database.




**Client (browser)**

- A single page app. Although the look of the screen and the URL may change, it should never load the whole page after the first page load.

- Use Vue/Nuxt.

- Allow the user to provide input to your application.

- Content must be catered to the user.

**Server**

- Write a custom server using NodeJS.

- Use either a NoSQL or SQL database (or both).

- Users must be able to create and use a login.

- Must manage user sessions.

- Users must be able to provide input and have a dynamic experience.

- The final project should be polished. It must look and act like a finished web application.

## Alone or with a Group

- You can work alone or in groups of two or three people.

- If you have more people working on the project then more will be expected of your final project.

## Project Proposal

Within the first few weeks of class we'll take time to discuss the project you'd like to work on. The purpose of this is two fold:

1. To help you create a project that is not too large and not too small.

2. To answer any questions you have about your project.

## Grading Criteria

The grade for your final project is based on a presentation that will occur on one of the last two days of class. There is no extra credit for presenting the first day. If any team fails to present they will receive a 0% on their final project.

The presentation should include a demonstration of the web application as well as some code examples. The following criteria will be used to grade your final project.

- **Attendance (5%)** - You must be there both days (one day to present, the other to see presentations).

- **Database Usage (10%)** - You must have your own database for storing data and your web application should read from and write to that database. (Show some code.)

- **REST API (15%)** - You must have several REST endpoints for sending data to the server and getting data back from the server. (Show some code.)

- **Single Page Application (15%)** - You're application should have the ability to navigate without reloading the page. You need to have at least three views (more if you have a team). (Show through demonstration.)

- **Session Management (15%)** - Users must be able to log into your system and remain logged in while navigating the site and during page reloads. Logout must also be available. (Show through demonstration.)

- **Polish (5%)** - I don't expect you to be a UI or UX expert, but I do expect the front end application to make sense and be usable without special instruction. (Show through demonstration.)

- **Project Scope (15%)** - Don't make your project too small. If you have questions about what is too small be sure to ask me. (Show through demonstration.)

- **Container Management (15%)** - You application needs to use Docker Compose so that it can be easily run from any computer that has container management capabilities.

- **Reward and Challenge (5%)** - Share with the class what the most rewarding part of the project was as well as the most challenging.

## Example Final Projects from the Past

- A calendar application that helps multiple users schedule on their own calendars or on a shared calendar.

- A recipe website where recipes can be submitted, categorized, searched by ingredients available, etc.

- A D&D tracking website.

- A puzzle video game.

- A project management application that tracks tasks across users and allows for team communication (posts, comments).

- An app to help manage a church calling.

- A photography application for uploading, categorizing, and searching photos.