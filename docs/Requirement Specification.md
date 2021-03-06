# 1. Introduction

## 1.1 Purpose
Meet John. He'll be our user. This app is out to make John's life so much easier and organised. When he's able to see clearly what he spends his time doing, John can become more productive. The App should enable the user to add notes and keep track of the notes. We expect John to log in his daily tasks, make changes to them and with a couple of clicks, John should be able to have an overview of his activities in a given time. To achieve this aim, we'll be implementing various techniques and software development tools
1. MongoDB will be used to store John's data
2. PHP on the backend, just ot mention a few.

## 1.2 Intended Audience
Our target audience is users like John who want to improve their current situation. It's a well proven fact that if we track our activities over time and document them, it'll be easier to make the changes required to become more productive.

## 1.3 Scope

The project scope is mostly defined by the size of our team. Our team is just big enough to to support a FullStack development of a simple project. Our manpower will be able to manage the full course of the development.

Monetary wise our project scope is zeroed, meaning we will use free and already available tools for the development.

Time wise our project scope is extremely restricted. We should allow documentation work until the end of October, then the actual development must begin.

# 2. Overall Description

## 2.1 User Needs
The user should be able to create, edit and delete notes within the app. The notes should be able to be given tags for sorting by category. Notes should be able to be assigned dates and times so that they can be organized by time, and a Daily, Weekly, and Monthly overview should be available. 

## 2.2 Assumptions and Dependencies
We are assuming the tasks are simple, and will not need extensive descriptions or things like checklists. We are also assuming this program will be used by one person at a time, and there will not be multiple user accounts on a single device. The project is dependant on the abilities of the team to work together to accomplish it. We will be using C#, PHP and MongoDB, so the software will be limited by the capabilities of those as well. 

# 3. System Features and Requirements

## 3.1 Functional Requirements
FR1: The web application allows the users to register.
FR2: For registration user has to provide a unique for the system username and a password. In case user cannot remember the password, they should be able to restore it. 
FR3: Once logged in, the users must see the list of their tasks. This page is the user homepage.
FR4: Users must be able to add new task and modify the old ones and delete ones that are not needed anymore.
FR5: Tasks include such attributes as name, date of creating the task and the deadline, category, and status(finished or not finished) and a field for any additional notes the user might want to include.
FR6: The "History" page displays the following information: the number of completed tasks, number of tasks in progress, average time for completing a progect, number of projects not finished in time and some further metrics.

## 3.2 External Interface Requirements
USER INTERFACES:
1. Home page (Log in button, register button)
2. User homepage (Add task, List of tasks, Log out button buttons; link to the history page)
3. History page
4. Task interface (called when user creates a new task or modifies an old one)

## 3.3 System Features
test

## 3.4 Nonfunctional Requirements

1) Our web application should be able to handle 10.000 users without affecting its performance.
2) We have to take into consideration the security parts of our app for example if user fails to enter credentials for three times we should suspend the sign in functionality for certain amount of time for example: 5 or 10 min 
3) we have to give suggestions for the user who is signing up, he or she better use special chars numbers alphabet etc. to make the password more secure, but it is not mandatory, which means user can use a very simple password as well 
4)  

