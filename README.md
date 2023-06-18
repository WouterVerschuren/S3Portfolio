# Semester 3 Portfolio Wouter Verschuren

## Table of contents:
- Intdroduction](#Introducation)
- Learning Outcomes](#Learning-Outcomes)
  - [1 Web Application](#1-Web-application)
    
      - [1.2 Designs](#desgins)
  - [3.2 Software Quality](#2-Software-quality)
  - [3.3 Agile Method](#3-Agile-method)
  - [3.4 CI/CD](#4-CI/CD)
  - [3.5 Cultural differences and ethics](#5-Cultural-differences-and-ethics)
  - [3.6 Requirements and Design](#6-Requirements-and-Design)
  - [3.7 Bussiness Process](#7-Bussiness-Process)
  - [3.8 Professional](#8-Professional)

## Introducation:

This Git repository contains all my projects, documentation and where to find everything

## Documentation
This folder contains all the documentation for my reasearches, designs and choices.

## Learning Outcomes
This folder contains both the Learning outcomes for the Group Project and the learning outcomes for the Individual Learning outcomes.

## Project
This folder contains all the project information. It consists of all the code and other information. 


## Learning Outcomes:

| # | Name | Short description | Clarification |
|---|------|-------------------|---------------|
| 1 | Web application | You design and build **user-friendly, full-stack** web applications. | **User friendly:** You apply basic User experience testing and development techniques.<br>**Full-stack:** You design and build a full stack application using commonly accepted front end (JavaScript-based framework) and back end techniques (e.g. Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues. |
| 2 | Software quality | You use software **tooling and methodology** that continuously monitors and improve the software quality during software development. | **Tooling and methodology:** Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well as applying static code analysis and code reviews. |
| 3 | Agile method | You **choose** and implement the most suitable agile software development method for your software project. | **Choose:** You are aware of the most popular agile methods and their underlying agile principles. Your choice of a method is motivated and based on well-defined selection criteria and context analyses. |
| 4 | CI/CD | You **implement** a (semi)automated software release process that matches the needs of the project context. | **Implement:** You implement a continuous integration and deployment solution (using e.g. Gitlab CI and Docker). |
| 5 | Cultural differences and ethics | You **recognize** and **take into account** cultural differences between project stakeholders and ethical aspects in software development. | **Recognize**:  Recognition is based on theoretically substantiated awareness of cultural differences and ethical aspects in software engineering.<br>**Take into account:** Adapt your communication, working, and behavior styles to reflect project stakeholders from different cultures;<br>Address one of the standard Programming Ethical Guidelines (e.g., ACM Code of Ethics and Professional Conduct) in your work. |
| 6 | Requirements and Design | You analyze (non-functional) requirements, elaborate (architectural) designs and validate them using **multiple types of test techniques**. | **Multiple types of test techniques:** You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance. |
| 7 | Business processes | You analyze and describe **simple** business processes that are **related** to your project. | **Simple:** Involving stakeholders, predominantly sequential processes with one or two alternative paths.<br>**Related:** Business processes during which the software that you are developing will be used (business processes that the software must support by fully or partially automating them).<br>**or**<br>Business processes needed for the success of your software development project (e.g., product release, market release, financial assurance). |
| 8 | Professional | You act in a **professional manner** during software development and learning. | **Professional manner:** You develop software as a team effort according to a prescribed software methodology and following team agreements. You are able to track your work progress and communicate your progress with the team.<br>You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions. You choose and substantiate solutions for a given problem. |

## 1 Web application

You design and build user-friendly, full-stack web applications.

Clarification:

User friendly: You apply best practices when creating user interfaces and basic user experience testing and development techniques.

Full-stack: You design and build a full stack application using a commonly accepted front end Javascript framework and back end application implementing relevant communication protocols, persistence of data by usage of ORM and addressing asynchronous communication issues.


### how I plan to show this learning outcome in my project: 

To show I have enough knowledge of this learning outcome I made a frontend webapp using javascript. To know which javascript framework I am going to be using for my frontend I have made a [Research Paper](https://github.com/WouterVerschuren/S3Portfolio/blob/main/Documentation/Researches/Javascript%20Framework.md) on which javascript framework would be the best for me and my project. For my backend I made a WepAPI using asp.net C#. My database is being hosted on azure. 

I started of with some designs. with these designs I show that I have knowledge of the design part of this learning outcome.

I choice a very simple design with a minamalistic/clean look. The reason I choice for this look is that urban explorers are usually people how are fairly young (around 17 to 30 year old). Since the most people around this age are fairly used to working on the internet the design will be very easy to follow for them. I also made sure to give the side a grayish tint. The reason I choice to do this is to is that urban exploring is for people how sometimes do sketchy/edgy things. to add to this vibe I made the site in a gray look. another reason for the simplistic design is that the webapp is pretty minimalistc it self as it doesn't have that many functionalities. so it doesn't need any fancy sidebar or things like that.
![Screenshot 2023-05-25 092850](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/76b26a15-1b85-4759-b9ad-4440650dd803)
on the first page you'll see all the location's that have been added to the map. once you click on one of these location you'll see information about the location and a route on how to get there.
location's that haven't been checked by a moderator will show on the map but will be a red color indicating that they haven't been checked and also won't show a route on how to get there. I do this so that when places are illegal to go to won't be trespast. the location that are checked will be displayed in a green color. I choice for bright colors so the points are easy seeable on the website.

![Screenshot 2023-05-25 092816](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/0b043c84-c056-487e-9274-aa9cc9602ec7)
on the second page you'll be able to add your own location to the site. you'll be able to add a name, location, infomation (such as information about the place and the route to get there) and you can add images you took. again I choice for a simple look here as will be easy to navigate for the people using it.

![Screenshot 2023-04-12 103940](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/b4fe2e88-f799-4486-87b5-6e1d2faaa049)
on the third page you'll be able to see places you added yourself to the map. you will also be able to delete or edit locations here. 

### UX Test:


#### the Three most commonly used usability testing methods are:

- Heuristic Evaluation:
with this method you evaluate a product's interface aginst it's usability principles. this method helps to look if there are any potential issues or violations in the product interfacce. this method of a usability test is very effiecient as it provides a list of problems that need to be changed or looked at.

- User Interviews:
with this method you have a direct interation with the individual user to gather their needs, feedback, expectations and challenges. this will help provide data on what the users want and expect and this can be usefull on making design and interface choices. this method is also very effiecient as it both helps gather feedback from the user and also help to find problems or other small things that need to be adressed.

- Thinking Aloud:
with this method you let the user verbalize their thoughts and actions while using the product interface. this enables you to see how users navigate the website. you can see when they incounter obstales and you can see when their decisions. this will help show the process of using your site and thus help you smooth this process to the users  needs.


I decided for my own usability test to use a mix of the user interview and the thinking aloud usability test. as these give in my opinion the best results when it comes to feedback, problems, user expectations and more usefull data.

#### UX:
##### UrbanExplorer (my brother):
my brother told me that the designs looked good. He really liked the minimalistic look as it helped him navigate the pages easily and made everything clear. Although he also said:” the minimalistic part also makes it a little childish”. “but then again the grayish style makes that not that important”.
Overall a good looking webapp and easy to navigate everything was easy to follow even tho I see it for the first time.

##### Digital Illiterate (My mother):
My mother thought the designs looked good aswell allthough she did think that the grayish wasn't as nice to look at. she thought there wasn't enough color on the page. however she did think this also was usefull as it made sure the location points are easy to see on the map. this meant for her that the this design feauture was good enough for her.


## 2 Software quality

You use software tooling and methodology that continuously monitors and improve the software quality during software development.

Clarification:

Tooling and methodology: Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well as applying static code analysis and code reviews.

### how I plan to show this learning outcome in my project: 
to show that I have enough knowledge of this learning outcome I made a test plan of what I am going to test. 


# Test Plan: 
### 1. UX test
### objective: make sure that the designs of the site are easy to follow and are clear.
### test scenarios:

verify that the user is able to use everything on the site as intended. 

verify that the User likes to designs and that they like the look.

#### UX test:
##### UrbanExplorer (my brother):
my brother told me that the designs looked good. He really liked the minimalistic look as it helped him navigate the pages easily and made everything clear. Although he also said:” the minimalistic part also makes it a little childish”. “but then again the grayish style makes that not that important”.
Overall a good looking webapp and easy to navigate everything was easy to follow even tho I see it for the first time.

##### Digital Illiterate (My mother):
My mother thought the designs looked good aswell allthough she did think that the grayish wasn't as nice to look at. she thought there wasn't enough color on the page. however she did think this also was usefull as it made sure the location points are easy to see on the map. this meant for her that the this design feauture was good enough for her.

### 2. User account managament
### Objective: make sure that users can create and manage their accounts.
### Test scenarios:

Verify that a user can register for a new account with valid information.

Verify that user registration fails with invalid or duplicate information.

Verify that a user can log in with valid credentials.

Verify that a user can’t log in with invalid credentials.

### 3. Adding and managing places
### Objective: make sure that a user can add places on the map, edit places information and delete places from the map.
### Test scenarios:

Verify that a logged-in user can add a new place with valid information.

Verify that adding a place fails when required information is missing or invalid.

Verify that a user can see all of the places they added.

Verify that a user can edit the details of a place they added.

Verify that a user can remove a place they added.

Verify that a user can view all the places on the map.

### 4. integration tests
### Objective: make sure the flow between backend and frontend works as intended.
### Test scenarios:

verify that a crud operation can travel between the database backend and frontend.

verify that the connection works between backend and frotend works as intended.


### the types of test I am gonna use with my test plan are: 
### 1. Unit tests

Unit tests are very low level and close to the source of an application. They consist in testing individual methods and functions of the classes, components, or modules used by your software. Unit tests are generally quite cheap to automate and can run very quickly by a continuous integration server.

### 2. Integration tests 

Integration tests verify that different modules or services used by your application work well together. For example, it can be testing the interaction with the database or making sure that microservices work together as expected. These types of tests are more expensive to run as they require multiple parts of the application to be up and running.

### 7. Smoke testing

Smoke tests are basic tests that check the basic functionality of an application. They are meant to be quick to execute, and their goal is to give you the assurance that the major features of your system are working as expected.

Smoke tests can be useful right after a new build is made to decide whether or not you can run more expensive tests, or right after a deployment to make sure that they application is running properly in the newly deployed environment.

### CodeScan:
I also added a code scan for my frontend project using soundcloud:

![Screenshot 2023-06-14 132521](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/f99e523f-ff7b-48d4-bd9a-7440dbc75727)

here you can easily see if there are any bugs, vulnerabilities and other problems with the code.




## 3 Agile method

You choose and implement the most suitable agile software development method for your software project.

Clarification:

Choose: You are aware of the most popular agile methods and their underlying agile principles. Your choice of a method is motivated and based on well-defined selection criteria and context analyses.

### how I plan to show this learning outcome in my project: 

To show I have enough knowledge of this learning outcomes I made a [research paper](https://github.com/WouterVerschuren/S3Portfolio/blob/main/Documentation/Researches/AgileMethods.md) about what agile methods there are and which would work the best for me.

Scrum:
Scrum Scrum is a popular Agile method and the one that I personally have the most experience with, as it is the recommended method within our study. since it is the most popular agile method to use. for our group project we choose to use scrum aswell.

the scrum process.
the scrum process starts with the creating of user stories. Once you have created the user stories they will be put on a scrum board. Every user story on the scrum board will be asigned a number. This will number (story point) will represent the expected amount of effert that is required to complete this user story. this way you can easily see how much time you are currently having to spend to finish the project. in the beginning of the project you'll make a planning using these user stories. when creating th planning you can look at the number you've given a certain user story and this will tell you how much time it is expected to cost. these user stories will then be placed in the backlog. Every morning you work on the project there will be a stand-up, this will be at a set location and time. in this stand-up session, which is usually around 15 minutes, you'll discuss the progress and or problems they made since the previous workday. they will also discuss the task they are gonna be working on that day.

during the duration of the project the workload will be distrubuted in sprints. Each sprint will be a step towards the end goal/product of the project. they should be able to be tested, usable and work together as a product. During the ending of each sprint there will be a presentation in which the engineers will show there work to the product owner as they review it and give there feedback. It will also help discuss any misunderstandings or problems with the project. after this presenatation the team will come together to do a retrospective. In this retrospective the team will discuss what went right, what went wrong, what they could have added and what they can add for next time. with this feedback they will start the next sprint until the last sprint when they will have a final presentation.

![blog-scrum-process-opt (1)](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/05c804b4-789b-4b8f-b1d7-c86590ef69ba)


Kanban:
Kanban With Kanban you make use of a kanban board. A kanban board is an agile project management tool desgined to help visualize your work. it also helps visualize your limit work-in-progress and it maximizes your efficiency.

A kanban board consist of cards and columns. Since the kanban board makes use of cards, where team members write all of there work items on, the kanban board is a very easy to read. You can easily see what is still left to do and what is done already. A card is usually a user story. Another thing that the kanban board has are columns. Each column you see on the kanban board represents a specific workflow. the cards flow thru this workflow until they are completed. a workflow can be something simple like "to do", "in progress", "complete" but they can also get more complicated.

another thing that the kanban board makes use of is work in progress limits (WIP limits). These limits are there to show the maximum number of cards in a column at any given time. so when a column has a WIP limit of 5. the column can only have 5 cards. when a column is full a team can focus on this column so that it they can add new cards to that flow. This will help the team members to find bottlenecks in there projects since you can see when you have to much work at once in the kanban board.

kanban boards also consists of a commitment and delivery point. a commitment point is the moments when a teams picks up one of the ideas from the backlog that's been added there by the team. The delivery moment is when the product is in the hand of the customer so basically when the product is done. A teams goal is to move cards from the commitment point to the delivery point as fast as possible.

kanban board
![480px-Sample_Kanban_Board](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/7e49e2af-de5a-4b39-9e44-2e596320672f)

## group project:

### Scrum boards:
#### [Frontend](https://github.com/orgs/Fontys-OAMK-Beter/projects/3/views/1) - [backend](https://github.com/orgs/Fontys-OAMK-Beter/projects/2)



for a group project we choose to make use of the scrum agile method as this felt for us as the best method to use. As I worked with this group before in group projects, I knew that it was important for us to have a good planning and structure in the group. Scrum makes use of sprints that are about 3-4 weeks long and makes use of a scrum board where everyone can see what everyone is doing and see what is still left to do. this will give good structure to the group where needed. In the first few sprints we didn't fully implement the scrum processes, but we made continous improvements as well we gained more knowledge about how to use scrum so in later stages we began to make improvements. 

since scrum is designed for unpredicatbale projects with its adaptability, flexibility and continuous improvemnt. it's also great for a group project as we work together with people finland it can sometimes be a little bit harder to communicate between choices and options. hence it can be usefull to use scrum for when unexpected decisions weren't as intended and cause problems. in this the adaptability of scrum will make it easier to fix the problems you have.

![blog-scrum-process-opt](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/55bd4668-b551-470c-9b0b-37cf404bbb63)



## 4 CI/CD

You design and implement a (semi)automated software release process that matches the needs of the project context.


Clarification:

Design and implement: You design a release process and implement a continuous integration and deployment solution (using e.g. Gitlab CI and Docker).

### how I plan to show this learning outcome in my project: 

To show I have enough knowledge of CI/CD I am hosting my frontend and back end in azure. I created a pipeline that deploys both applications using a github action. I also added CI to this pipelin so that I use continues integration. I made sure that in this pipeline all my test are getting called aswell. once a test fails the project won't be able to deploy and when all tests are past without errors then it will deploy. This will help show if there are any errors in my project.

my pipeline:

![Screenshot 2023-06-14 123845](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/92b685ae-627f-4e48-b9bf-9cbf9cba4575)

## 5 Cultural differences and ethics

You recognize and take into account cultural differences between project stakeholders and ethical aspects in software development.

Clarifications:

Recognize: Recognition is based on theoretically substantiated awareness of cultural differences and ethical aspects in software engineering.

Take into account: Adapt your communication, working, and behavior styles to reflect project stakeholders from different cultures;

Address one of the standard Programming Ethical Guidelines (e.g., ACM Code of Ethics and Professional Conduct) in your work.  

### how I plan to show this learning outcome in my project: 

## What is culture?
For me Culture is the beliefs, values and behvaiors someone has. people from the same culure usually connect on most of the same beliefs, values and behaviors as other people from the same culture. This gives culture the feeling of belonging. Cultures include traditions, languages, arts, sociol norms and knowledge. 

## what is my culture?
As a person who is dutch I tend to have a lot of trades from dutch culture. the most common of these trades is probably dutch directness. Dutch people usually tend to say what's on there mind and not think to much about what comes out of their mouth. This can both be a good thing and a bad thing, since it helps to show your opinion about something. but it can also be too direct sometimes and can be seen as offencif when you say something a bit too agressive. this is especially true when you're speaking with someone from a different culture where this is less common.


## What did you do to improve the group communications with respect to cultural differences?
For our group project we are currently working together with people from finland. Usually Finnish people tend to be a bit shy when you meet them for the first time and take a long time opening up. this sometimes made it diffecult to know if they were okay with certain decisions we made as they wouldn't be as harsh as we dutchies are used to. because of this we decided to make decisions we made them very clear so that they had enough time to give their honest opinion about them. We also made clear rules about everything so that everything was much easier to communicate between the group this helped everyone feel comfortable in both groups. As for myself I tried to be a lot calmer and softer with my replies as saying things to harsh could make the finnish people feel uncomfortable. We also had a group discord where we could discuss all our problems and ideas. This also helped us keep a good commmunication.


## 6 Requirements and Design

You analyze (non-functional) requirements, elaborate (architectural) designs and validate them using multiple types of test techniques.

Clarifications:

Multiple types of test techniques: You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance.

### how I plan to show this learning outcome in my project: 

to show I have enough knowledge of this learning outcome you've have previously seen [some designs](#1-Web-application) I made for my individual project. 
To test these user designs I created some simples user tests. 

To test my designs I got a few users to look at them and give me advise and/or feedback. I made sure to use different groups of people to make sure my designs where as good as can be. 



![Screenshot 2023-06-07 205314](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/4ac0877b-abcc-4be5-b5a7-1e76eca1930c)

I also made User stories both for my individual project and group project. for my individual project I only put the user stories in a board to see what I have left to do. but for my group project we also performed scrum on it. this user stories helped me to see what I had left to do and see what I had finished.

group project user stories:

![Screenshot 2023-06-14 122835](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/29648074-e73d-4df1-adcc-a7850a4d6fbd)


individual user stories:

![Screenshot 2023-06-14 123120](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/0e9bb2b4-c22e-4ead-82e3-b3076f3e9803)

I also made designs for our group project:

![Screenshot 2023-06-14 125516](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/155a701a-b7c7-4d2f-9c04-38324541c460)

![Screenshot 2023-06-14 125449](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/60a61411-9302-4c87-b309-2c43d9e44716)

![Screenshot 2023-06-14 125420](https://github.com/WouterVerschuren/S3Portfolio/assets/74074356/beeef855-b44d-4c8e-89bd-2aea44fb03ee)


## 7 Bussiness Process




You analyze and describe simple business processes that are related to your project.

Clarifications:

Simple: Involving stakeholders, predominantly sequential processes with one or two alternative paths.
Related: Business processes during which the software that you are developing will be used (business processes that the software must support by fully or partially automating them).
or
Business processes needed for the success of your software development project (e.g., product release, market release, financial assurance).

### how I plan to show this learning outcome in my project: 

## stakeholders analysis:

### what is a stake holder?
A stakeholder can be an person, group or organization that's impacted by the outcome of a project or business venture. The most important thing for a stakeholder is the succes of the project. The reason stakeholders are important in the project is that they can either have a positive or negative influence on the project with their decisions. Because of these influences that the stakeholders has it's important to choose someone who is fitted for the job to bo the stakeholder.

### Who are the stakeholders in my project and what are their goals and constraints? 
For our project We have three stakeholders: Frank, Samuil and Meija. their goal is to keep watch over the project and make sure everything goes as planned and the project ends in a succesfull way. to do this they look at the project together with engineers to make sure everything goes as planned and as was intended.

## Process analysis:

you'll find my business process [here](https://github.com/WouterVerschuren/S3Portfolio/blob/main/Business%20process%20analysis.md)

### What is a business process? 
A business process is an activity or multiple activities that accomplish a specific organized goal. The goal of a business process is to produce a consistent outcome and to be as specific as possible to do this. a bussiness project should have a purposeful goal.

### How does a business proces relate to software applications? 
BPM (Business Process management) relates with software in multiple ways:

- Automation and Efficiency: Software applications are often developed to automate and streamline business processes. by optimizing the technology organiztions can elimninate manual and time consuming tasks and this will make the efficiency higher.

- Workflow and Collaboration: software applications enforce the flow of the task and information within the business process. they provide a way to collaborate and communicate between employees, group members and stakeholders involved in the project. 

- Continuous Improvement: A business evolves and gets bigger over time. to support this contious growing and evolvement, software applicatoin can help by prividing flexibility, scalability and the ability to implement changes. When making use of feedback and iterative cycles software applications can be made to align witht the growing business requirements.




 

## 8 Professional

You act in a professional manner during software development and learning.

Clarification:

Professional manner: 

You develop software as a team effort according to a prescribed software methodology and following team agreements. You are able to track your work progress and communicate your progress with the team.

You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions.
You choose and substantiate solutions for a given problem.

### how I plan to show this learning outcome in my project: 

To show that I have enough knowledge of this learning outcome I made sure to ask feedback from my stakeholders and teachers. in the group project I did this in the form of showcases of our project where we got feedback from the stakeholders. once we got the feedback we made sure to discuse it in our group. for the individual project I made sure to ask for feedback from my teacher. I made sure to post this feedback in feedpulse so my teacher can clearly see what has been discussed and how I am planning to accomplish the things discused and explained. for our group project we also wrote peer reviews for eachother. this way everyone in our group could see where they could make improvements and see what they were doing good.
