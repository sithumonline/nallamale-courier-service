# Nallamale Courier Service

__This is imaginary courier service that is used to demonstrate the use of the system design principles__

Nallamale company is a startup that is into courier services. They have management team, operations team,
sales and marketing team, engineering team and delivery agents. 
They have Engineering team with;

- 5 developers
- 2 QA engineers
- 1 DevOps engineer
- 1 Business Analyst
- 1 Project Manager
- 1 tech lead
- UI/UX designer

## Requirements

## Branches

- Packages should be able to be entered into the system from the branch
- Branch should be able to register delivery agents
- Branch should be able to assign a package to a sender
- Branch should be able to track all packages
- Branch should be able to update the status/location of a package/packages

## Senders/Receivers

- Senders/Receivers should be able to track their packages

## Delivery Agents

- Delivery agents should be able to update the status/location of a package
- Delivery agents should be able to view all packages assigned to them

## How this unreal company works

1. BA will get the requirements from the management team, operations team and delivery agents for each quarter.
2. BA will then create a document with all the requirements and review it with the engineering team.
3. BA will prioritize the requirements with the help of the management team and operations team.
4. BA will share the requirements with the engineering team.
5. Tech lead will create a document with all the design details and share it with the engineering team.
6. Project manager will create epics and stories for design and share it with the engineering team.
7. UI/UX designer will create the UI/UX design for the epics and stories.
8. Tech lead will break down the design into tasks and estimate the time required to complete each task with the help of the engineering team under the epics and stories.
9. Project manager will assign the tasks to the engineering team.
10. Engineering team will start working on the tasks.
11. QA team will start writing test cases for the tasks.
12. QA team will start writing automation scripts for the tasks.
14. After the tasks are completed, DevOps engineer will deploy the code to the test environment.
15. QA team will test the code in the test environment.
!6. After the code is tested, DevOps engineer will deploy the code to the production environment.

## Tools and Technologies

### Project Management

- Jira
- Confluence

### Design

- Excalidraw
- Figma

### Development

#### Frontend

- Next.js
- Tailwind CSS

### Backend

- Javaspring/Golang/.NET
- MongoDB

Backend will be developed using microservices architecture.

When we comes to languages, we will be using Javaspring, Golang or .NET. We will be using MongoDB as the database.

## Design

### High Level Design

We need frontends for the following users;
- Branch
- Sender/Receiver
- Delivery Agent

### Services and APIs

CRUD services:
- User Service
= Package Service
- Branch Service
- Delivery Agent Service

Handle payments:
- Payment Service

Handle notifications:
- Notification Service

Aggregate services:
- BFF
