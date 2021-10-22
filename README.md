# JIRA_Ticket_Clone
Task Manager

## Tech-Stack

* HTML 5
* CSS
* Vanilla Js
* Bootstrap 
* shortid

## Prerequisite concepts
* DOM
* Html & css concepts


# Documentation

Following is a brief documentation of the Jira Ticket clone application. Concepts such as states,localStorage, etc. will be discussed.

## States

A state is as the name says describes the current state the program is in and is necessary and sufficient to conclude the program. In this project there are 2 states that follows the conditions namely: 

**1. General - No prefernce**
	General state is achieved when the tickets doesn't have priority set. The program gets to this state when the user just opened the website.

![general state](https://github.com/amaan0o7/JIRA_Ticket_Clone/blob/main/images/Capture.PNG)

**2.Priority**
	The program is in the *Priority State* when the ticket is getting color prefernce by the user for filtering the priority based on the task.
The program can get to this state when the user clicks one of the four colors in the Navigation Bar.

![Priority](https://github.com/amaan0o7/JIRA_Ticket_Clone/blob/main/images/4.PNG)

## Control Flow through buttons

The program is being controlled by two buttons namely: Add/Remove and Priority button. 

**Add button:**
User can only click Add button in the General states. As soon as the Add button is clicked the program open the Modal. 
Modal has functionalities:-
* Task Info
* Color of the Ticket
![Modal](https://github.com/amaan0o7/JIRA_Ticket_Clone/blob/main/images/3.PNG)

**Remove Button:**
Remove button is a single button that is acting as for removing the Ticket. User can click the Remove button in general or Priority state.

![remove](https://github.com/amaan0o7/JIRA_Ticket_Clone/blob/main/images/2.PNG)

# [LoadStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage): 
The localStorage read-only property of the window interface allows you to access a Storage object for the Document's origin, the stored data is saved across browser sessions.
![Modal](https://github.com/amaan0o7/JIRA_Ticket_Clone/blob/main/images/5.PNG)


